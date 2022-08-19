# READ ME DEMO
Agik practice code

## ls -la:
List everything including hidden folder
## ls | grep  agik-git-key
Search for a file by name
## untracked
Git does not know about the file, not commited or newly created
## Git ssh key
ssh-keygen -t rsa -b 4096 -C "agikedwin@gmail.com"

## ssh key location
(/home/agik/.ssh/id_rsa): agik-git-key)

#Link local repo to the remote repo
git remote  add origin https://github.com/Agikedwin/demo-git-tut2.git

Check remote version: git remote -v

Ignore master or branch: set upstream: git push -u origin master

##Git branching

Master branch is the naming convention for the main or default branch

Feature branch: at the start master and feature branches are same, as you make changes , the changes are only seen on the feature branch

#Git branch
git branch: list branch
git checkout -b git-demo-feature-1: creates new branch
git checkout master : switch to master
git merge : merge branch and master




