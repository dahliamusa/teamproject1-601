# Fork

A **fork** is a copy of a repository that functions as an 
independent project separate from the original. A fork can 
be done within GitHub by clicking on project repository name, 
and then clicking the Fork button.

In the terminal, there is no explicit "fork" command. To fork in 
the terminal, you need to get the URL of the repository you would 
like to copy and then [clone](/clone.md) it. Then, use the command 'git remote 
add upstream [url]'. To update your fork, you need to [pull](/pull.md) using 
'git pull upstream master', and to [push](/push.md) your changes, use 
'git push origin master'.

Sources:
* [What is Git Fork and How to Fork a Repository in GitHub?](https://www.toolsqa.com/git/git-fork/#:~:text=Git%20Fork%20is%20a%20simple%20process%20in%20GitHub,the%20same%20are%20covered%20in%20the%20next%20section.)
* [Forking Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow)
* [Quick Tip: Sync a GitHub Fork via the Command Line](https://www.sitepoint.com/quick-tip-synch-a-github-fork-via-the-command-line/)