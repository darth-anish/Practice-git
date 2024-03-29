# Welcome to the README

## TOP GIT COMMANDS
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
- hard-reset
	- to reset the HEAD to any previous commits, removing all files and changes completely: git reset --hard <commitId>
- mixed-reset 
	- files are kept locally but removed from the staging area/index, you have to add and commit to return back to original HEAD: git reset --mixed <commitId>
- soft-reset
	- files are kept locally in staging area, only commit is needed to return back to original HEAD: git reset --soft <commitId>
- stash
	- save modified and staged changes: git stash
	- list all stashed file changes: git stash list
	- write working from the top stacked stash: git stash pop
	- drop a stash from the top of the stack: git stash drop
