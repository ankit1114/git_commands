# Git_Commands

* git init
(This command is used to start a new repository.)

* git status
(This command lists all the files that have to be committed.)

* git add [file] 
(This command adds a file to the staging area)

* git commit -m “[ Type in the commit message]”  
This command records or snapshots the file permanently in the version history.)

* git remote add origin https://github.com/user/repo.git 
To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored at.)

* git push [variable name] master 
(This command sends the committed changes of master branch to your remote repository.)

* git push -f/-u origin master
:- git push -f origin master
* git pull https://github.com/user/repo.git 
(This command fetches and merges changes on the remote server to your working directory)

* git branch 
(This command lists all the local branches in the current repository.)

(a) git branch [branch name]  (This command creates a new branch.)

(b) git branch -d [branch name] (This command deletes the feature branch.)

* git checkout [branch name]
(This command is used to switch from one branch to another.)

*git checkout -b [branch name] 
(This command creates a new branch and also switches to it.)

* git merge [branch name]  
(This command merges the specified branch’s history into the current branch.)

*git stash

* git stash save  
This command temporarily stores all the modified tracked files.

* git stash pop  
This command restores the most recently stashed files.

* git stash list  
This command lists all stashed changesets.

* git stash drop  
This command discards the most recently stashed changeset.

* git rm [file]  
This command deletes the file from your working directory and stages the deletion.

* git reset [file]  
This command unstages the file, but it preserves the file contents.

* git diff –staged 
This command shows the differences between the files in the staging area and the latest version present.

* git diff [first branch] [second branch]  
This command shows the differences between the two branches mentioned.
