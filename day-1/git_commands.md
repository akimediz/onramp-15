Initializing git
git init

git add ==> add file to staging area or keep track of changes made.
git add . / git add <fileName>

git rm --cached <file>..." to unstage

git status ==> shows status of working directory and staging area

git commit ==> commiting changes to local repo

creating remote repo for my local repo
git remote add origin <remote repo location>

if I want to change the branch 
git branch -M main

Pushing into the remote repo
git push -u origin main/master

merging new branch into main
git merge <branchName>

to pull changes from github
git pull

`git branch <branchName>` ==> creating a new branch

`git checkout <branchName>` ==> changing branch

`git clone <github http url>` ==> use to download a copy of the remote repository into our local machine
