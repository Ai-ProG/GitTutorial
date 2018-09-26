# GitTutorial

Basic Git Steps
Create a new repository

1.git init
2.git status
3.git add <filename>
4.git commit -m "message"

git push https://github.com/Ai-ProG/<filename>.git master 
 
git remote add origin https://github.com/Ai-ProG/<filename>.git {git remote -v}
git push -u origin master {origin=alias}
  
Working with others(make sure you are in master)
===========
git clone <link> -->cd new-folder  

git pull origin master

git checkout -b <filename>
 make changes in new branches file
 
git add .
git commit -m " edited new things"
==
review in github by others
==
git checkout master
git pull origin master

git push origin <filename> --- compare and write comment what have you done -- pull request
 --merge pull request(confirm merge)--delete branch since it is merge to origin

Some request to change 
git checkout master
git pull origin master
git checkout -b newbranchname
git commit -m "new things done"
git push origin newbranchname

missing something
add missing file
=========
git add .
git commit -m "added"
git push origin newbranchname
