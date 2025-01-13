# Git Branching Cheat Sheet

## Basic Commands
* `git init` - initialize local  repository in current working directory
* `git add fileName` - stage `fileName` for commit
* `git commit -m "msg"` - commit staged changes with commit message `msg`


## Info Commands
* `git status` - report status of working directory
* `git log ` - list commit history of local repo
* `git log --oneline` - list commit history (compact format)
* `git branch` - list local branches

## Branching Commands
* `git branch branchName` - create local branch `branchName`
* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b branchName` - create (if not exists) `branchName` and swith to it

## Remote Commands
* `git remote add alias repoUrl` - define `alias` as shortcut for `repoUrl` (usually `origin` for alias)
* `git push origin branchName` - push local commits to remote brach `branchName`
* `git pull origin branchName` - pull remote commits into local branch 