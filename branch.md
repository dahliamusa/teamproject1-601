# Branch

A **branch** consists of a series of *commits*. Branches allow you to 
work on a specific feature or function of a project without making changes 
to the main working version of the project. If you are adding a new feature 
to your software, for example, and decide that you no longer want the 
feature, you can still access the old version of the project. By removing 
the branch containing the undesired feature, you can easily revert to a 
previous state of the project.

A project typically has a *master branch*, and this is the project's main branch. 
The other branches will connect to the master branch either directly or indirectly. 
The diagram below illustrates GIT branching. Each circle represents a commit, and 
each color represents a different branch. As you can see, it is the master branch 
that is central in this project.

![Image of branching](https://www.f30.me/wp-content/uploads/2013/05/git_branching.png)

To create a branch, use the 'git branch' command followed by the name you would like 
to give the branch.

Sources:
* [Branch in Git](https://www.toolsqa.com/git/git-alias/)