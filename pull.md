# Pull

A **pull** updates changes from the remote branches to the working directory. It is a combination of `git fetch` and [`git merge`](/merge.md) where the remote branches are "fetched" and then "merged" into the current branch of the working directory. On a platform such as GitHub, the users are able to create pull requests in order to merge commits to the working directory. If the branch has no conflicts with the base branch, then the pull request can be formally merged with the base branch. Otherwise, the command `git pull` in a terminal can also achieve the same effect without creating a pull request.


![Git Pull](/C://Users/Yunduo/Documents/Maggie/IS6011851/TeamProject1/gitpull.png)

Sources: 

*[Git Pull](https://github.com/git-guides/git-pull)
