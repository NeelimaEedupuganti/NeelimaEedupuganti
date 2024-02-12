# Welcome to Git Basics

Create dir using

mkdir <dir_name>

To go nto that working dir

cd <dir_name>

To initiliize local git repo use the cmd

git init

to write code use

code .

Open new file to write code and save it

use "git add" to track

git add C:\Users\manik\documents\github\README1.md

To add all files and folders in the <dir_name>

git add .  

Comit the latest files and folders

git commit -m "<commit_message>"

To push fro local to github

git push

To check status use

show status


steps for creating new branch and clone 

First check the status
git status

To clone the project from repo
git clone <https://github.com/learndataengineering/learndataengineering.guide.git> 
URL of repo 

create new branch
git checkout new_branch

To add some new changes to existing file open some IDE 
code .

To add the changes to existing file
git add .
 
this is to commit the file
git commit -m "add hadoop ecosystem components in index.md file"
git commit -m <" heading <filename> file">

to push the file 
git push --set-upstream origin newbranch
 