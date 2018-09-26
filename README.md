# GitTutorial
======================
Basic github tutorials (Steps)
======================

To begin, open up a terminal/cmd and move to the directory(cd command) where your project is.
To initialize a git repository use --> git init
Create a new file for your project.
After creating the new file, you can use the -->git status command to see which files git knows exist.
Write few lines of codes in your new project file.
Now to add a file to a commit, you need to add it to the staging environment. To do this,
use --> git add <filename>
Now, added the file you want to staging environment, you can commit using the-->git commit -m "Your changes done message".
Check using -->git status
  
Basically 3 things in git 
1.Modified: Changes made in the project.
2.Staged: You edited your file and ready to commit.( Cached Zone)-->git status--->git add<filename>-->git status
3.Committed: The data is saved in your database/git repository.-->git commit -m "  msg "

To remove from staging area use : git rm --cached <filename>
--------------------------------------------------
To see the history use: git log {option --oneline}
  
  Methods to reset [ Checkout commit--Revert commit--Reset commit ]
   git checkout <id> --- revert back to the id what was done
   git checkout master --- get back to original.
  
   git revert <id> --- undo the file what done in given id
  
   git reset <id> --- removes all the commit afterward but they will be in staging area
   git reset <id> --hard ---removes totally.
