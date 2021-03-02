Version 1.0.0 of Semantic Versioning, by Tom Preston-Werner of GitHub fame, had a sub-specification addressing this:

    Tagging Specification (SemVerTag)

    This sub-specification SHOULD be used if you use a version control system (Git, Mercurial, SVN, etc) to store your code. Using this system allows automated tools to inspect your package and determine SemVer compliance and released versions.

    1. When tagging releases in a version control system, the tag for a version MUST be "vX.Y.Z" e.g. "v3.1.0".

However, after discussion this was removed, and is no longer present in the latest version of the SemVer spec (2.0.0 at the time of writing). A later discussion thread in the same place went into greater depth, and resulted in a new Is "v1.2.3" a semantic version? being added to the FAQ in SemVer's master branch, although at the time of writing (over 2 years later) this change is still not present in the officially released spec.

[Is there a standard naming convention for git tags? [closed]](https://stackoverflow.com/questions/2006265/is-there-a-standard-naming-convention-for-git-tags)
[Semantic Versioning 2.0.0](https://semver.org/)
`answered Jan 6 '10 at 6:50`
`peritus`