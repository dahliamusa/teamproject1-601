# GitFlow

GitFlow is a workflow design based on a branching model in which parallel development can occur easily because it is designed around the project release. It is ideal for managing larger projects with a schedule release cycle in which specific roles are assigned to different branches: `master`, `develop`, `feature`, `release`, and `hotfix`. 

## Definitions

### Master

It is the branch in current production. The `master` branch will store the official release history of each version.

### Develop

It is the branch in which complements the `master` branch as a staging area. New features are merged into the `develop` branch after being developed in the `feature` branch and polished in the `release` branch.The `develop` branch contains the complete history of the project.

### Feature

It is the branch for exploration and new experimentation. By creating a `feature` branch off of the `develop` branch, it allows for one team to continue exploring new features while another team can be preparing for a new release based on the current features.

### Release

The `release` branch is where the next release cycle starts, and no new features will be added at this point. It is polished and merged into `master` once it is ready. It should also be merged back into `develop` in case other developments have ocurred since the initiation of the release.

### Hotfix

It is the maintenance branch of the workflow. It is used to quickly patch production releases based off of the `master` branch directly. Once the fix has been completed, it should be merged into both the `master` and `develop` branches as soon as possible since it will contain the most recent version number.

## Flow Chart

The overall flow of GitFlow is the following:
1. A `develop` branch is created from `master`.
2. A `feature` branch is created from `develop`
3. New features are built in `feature` and merged back into `develop` when it is ready for release.
4. A `release` branch is created from `develop`.
5. After the `release` branch has been tested, it is merged into `master` and `develop`.
6. If an issue in `master` is detected, then a `hotfix` branch is created from `master`
7. After `hotfix` has been resolved, it is merged into `master` and `develop`.


Sources: 
* [Introducting GitFlow](https://datasift.github.io/gitflow/IntroducingGitFlow.html)
* [Gitflow Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)