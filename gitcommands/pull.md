# Pull

A **pull** updates changes from the remote branches to the working directory. The command `git pull` is a combination of `git fetch` and [`git merge`](/gitcommands/merge.md) where the remote branches are "fetched" and then "merged" into the current branch of the working directory. On a platform such as GitHub, the users are able to create pull requests in order to merge commits to the working directory. If the branch has no conflicts with the base branch, then the pull request can be formally merged with the base branch. 


![Git Pull](../images/gitpull.png)

Sources: 

* [Git Pull](https://github.com/git-guides/git-pull)