# INTRODUCTION
### Prerequisites
### Version Control(Snapshot every stage of your work and you can revert, track, modify, and compare changes. etc )
* Local version control--VCS. On your own hard drive
* Centralized Version Control--CVCS. Based on a main single server and allow team members to collaborate
* Distributed Version Control--DVCS. Create mirrored repositories to eliminate the risk(single server goes down and lost all the data)
### What is Git?
* Git is DVCS. You can do your work on your own disk. Git will create snapshot and make it difficult to lose data.
### Installation and Setup--done
### Set up Git Repository
* switch directory--cd foldername
* git init command--git init
* some commit command:
  * git add xxxx
  * git commit -m "any message here"
### Cloning
* Clone an existing git repository from server--git clone https://github.com/test
### Workflow
* Locoal repository structure
  * working directory--where actual files at
  * index-staging area
  * head--most recent commit
### Saving Changes
* Tracked
* Untracked
### Life Cycle of File Status
* Add>Edit>Stage>Commit(Remove)
### Check File Status--git status
* "working directory clean"--means files have tracked or modified at this moment
### Tracking and Staging a New File
* Single File--git add filename
* All Files--git add *
* don't forget check status--git status
### Committing a file--git commit -m "what change you made"
### Committing All Changes--git commit -a
### Pushing Changes--git push origin main(just changed master to main)
### Stashing Changes--git stash(temporarily hide and save your change)---git stash apply(retrieve the hidden changes)
### Remote Repositories
* Cloned Repositories--Git will automatically give "origin" to the original server and "main" to your local branch
* Seeing Your Remotes
  **view short names--git remote
  **view all remote URLs--git remote -v

  [<--Back](README.md)









