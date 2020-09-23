# Repository

A **repository**, also called a repo, is a directory where files for a 
certain project are stored. When working on a project, it is common to 
have local and remote repositories. A local repository is saved to your 
local machine, and it is where you would do your individual work. A remote 
repository is the common repository containing the combined work of all 
contributors. When you have any completed code segments in your local repository, 
you would send your work to the remote repository, or [push](/gitcommands/push.md) it, 
so that it can be added to the remote repository. Services like GitHub 
are usually used to manage remote repositories.

To create a new local repository, you need to have an existing directory which 
you would like to turn into a project repository. First, cd into the directory. 
Then, use that `git init` command, and your directory will become a local repository.

![git_init](https://vegibit.com/wp-content/uploads/2018/05/git-init.png)

If you are going to start working on an existing project, however, you likely 
won't be creating a new repository locally. Instead, you would create a local 
copy of a remote repository, and to do this, you will need to clone the remote 
repository. For more information on cloning a repository, check out the 
[clone](/gitcommands/clone.md) page.

Sources:
* [How to Create and Manage Your First Git Repository](https://www.bitdegree.org/learn/what-is-a-git-repository#:~:text=Git%20Repository%3A%20Summary%201%20Git%20system%20stores%20and,is%20a%20copy%20of%20a%20remote%20Git%20repo.)
* [Git init](https://github.com/git-guides/git-init#:~:text=git%20init%20is%20one%20way%20to%20start%20a,creates%20as%20a%20part%20of%20your%20project%27s%20history.)