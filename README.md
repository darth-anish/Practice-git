# Welcome to the README

In this repository we'll learn how to use basic git commands such as :
- branch
	- to see all branches: git branch
	- to create a new branch: git branch <branchname>
	- to switch branch: git switch $branchname
- commit
	- commit the changes: git commit -m "<commit message>"
- add
	- to add all files as it looks now to staging: git add .
	- to add a specific file as it looks now to staing: git add <filename>
- diff
	- to see changes which are not staged: git diff
	- to see changes staged but not commit: git diff --staged
- log
	- to see logs of changes: git log <branchname>
	- to see quick status/log change: git log --oneline
- fetch
	- to get all remote branches into local machine: git fetch
- pull
	- to fetch remote branches and merge changes to local branch: git pull

- push
	- to push all local commited changes to remote branch: git push origin <branchname>
- revert
- reset --hard
- reset --soft
- reset --mixed

