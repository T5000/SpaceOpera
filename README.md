# Branch naming convention.
[main] contains commits pertaining to the repository's structure and administration, like changes to this file.
[release] contains stable commits approved for usage in sessions.
[dev] is the main development branch of the project. Branch features from it, merge complete features back into it. Do not commit to this branch, except for merge conflict resolution and other maintenance purposes.
[feat-<feature name>] contains development of a feature. Branch this one from [dev] and merge it back into [dev] once the feature is complete.
[exp-<name>] contains an experiment not related to a specific feature. Do not merge these into [dev].
