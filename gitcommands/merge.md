# Merge

**Merge** will join multiple [branches](/gitcommands/branch.md) or sequences of 
commits into a single branch, creating one unified history. The 
target for the merge is always the [checked out](/gitcommands/checkout.md) branch.

To merge, first make sure you have checked out the right branch. 
Then, use the `git merge` command followed by the name of the branch to 
merge. If the branches cannot be merged, a merge conflict message will appear.

![git_merge](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/58a4dc22_ud123-l5-git-merge-conflict/ud123-l5-git-merge-conflict.png)

Sources:
* [Git Merge](https://www.atlassian.com/git/tutorials/using-branches/git-merge)