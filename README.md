# git-task 

## Definition of Version control
Version control is a system that tracks changes to file over time, allowing multiple people to collaborate on a project. It maintains a history of modification, enabling users to revert to previous states, compare changes, and work on a separate branches

## Difference between git and github
Git is a distributed version control system that allows tracking changes in source code during software development. GitHub on other hand, is a web-based platform built around Git. It provides additional features like a centralized repository hosting service, collaboration tools, and a web interface to manage repositories. GitHub allows multiple developers to work on projects, facilitates collaboration, and offers features such as issue tracking, pull requests and code reviews. In summary, Git is the version control system, while Github is a platform that uses Git for version control and adds collaboration services on top of it.

## Lists of other github alternatives
Other GitHub alternatives - 
1. GitLab 
2. Bitbucket 
3. SourceForge

## Differrence between git fetch and git pull
The difference between git fetch and git pull- git fetch is a Git command that retrieves changes from a remote repository to your local repository. When you run git fetch, Git contacts the remote repository specified (usually named "origin" by default) and fetches any new branches or changes that have occurred since your last update while git pull is a Git command that combines two operation: fetching changes from a remote repository and merging them into the current local branch. It is essentially a shorthand for running git fetch and git merge.

## Explanation of git rebase and the command for it
In simple terms, git rebase is a Git command used to change the base of your branch, typically to incorporate changes from another branch. It rewrites the commit history to make it look like you branched off from a different commit. The commmand for git rebase is: git rebase <code>base-branch</code> 

## Explanation of git cherry-pick and the command for it
In simple terms, git cherry-pick is a command that let you copy a specific commit from one branch and apply in onto another branch. It allow you to pick and choose individual commits to bring into a different branch. The command for it is: git cherry-pick <code>commit-hash</code>