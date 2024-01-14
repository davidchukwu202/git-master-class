# git-master-class

Version control is a system that enables multiple people to work on a project simultaneously without interfering with each other's work. It is a system that manages changes to a project's source code or any set of files over time.

Difference between git and github

Git and GitHub are related tools, but they serve different purposes in the context of version control and collaborative software development.
Git works locally on a developer's machine while github is web-based.
Git is the version control system that manages the source code, while GitHub is a web-based platform that provides a hosting service for Git repositories along with collaboration features.

3 other github alternatives

SourceForge
GitLab
Bitbucket

The difference between git fetch and git pull,

git fetch retrieves the latest changes from the remote repository but does not automatically merge or modify your working directory
While
git pull fetches the changes from the remote repository and automatically merges them into the current branch.


Git rebase and the command for it


git rebase is a Git command that allows you to move or combine a sequence of commits to a new base commit.

With git rebase, instead of creating a new merge commit, your changes are applied on top of the changes from the remote branch, effectively moving or rewriting your commit history to make it look like you branched from the updated remote state.

    git checkout develop
    git rebase main

Git cherry-pick and the command for it

git cherry-pick is a command that helps you selectively copy and apply a single commit from one branch to another. It's useful when you want to bring a specific change without merging the entire branch.

    git checkout develop
    git cherry-pick <commit-hash>
