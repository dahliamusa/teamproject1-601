#GitFlow

GitFlow is a workflow design based on a branching model in which parallel development can occur easily. It is ideal for managing larger projects with a schedule release cycle in which specific roles are assigned to different branches. 

The overall flow of GitFlow is the following:
1. A `develop` branch is created from `master`.
2. A `feature` branch is created from `develop`
3. New features are built in `feature` and merged back into `develop` when it is ready for release.
4. A `release` branch is created from `develop`.
5. After the `release` branch has been tested, it is merged into `master` and `develop`.
6. If an issue in `master` is detected, then a `hotfix` branch is created from `master`
7. After `hotfix` has been resolved, it is merged into `master` and `develop`.