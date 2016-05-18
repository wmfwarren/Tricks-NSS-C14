# Basic Git Commands

### Git *ACP* Workflow
1. add
1. commit
1. push

2. git add *fileName*
2. git commit -m "*message*"
2. git push origin *branchName*
	* add a *-u* flag the first time you push

### Cloning
1. git clone *SSH/HTTPS address*
 * This copies a repo to your local machine. It allows you to push if you have permissions, too. It is not a fork.

### Branching
After you clone the master branch make your own by:
1. git checkout -b *branch name*
	* Now you have a copy of master that can be worked on without messing up master.
1. git branch
	* this will show you all your branches and your current branch with a '*'
	* Your can do the ACP workflow to push this to GH.
1. git branch -D *branch name*
	* THis deletes a branch after you no longer need it (i.e. because it is merged into the master on git)

### Pulling
1. git pull origin *branch name*
	* Pulls down a branch from GH to update it locally once merges occur.


