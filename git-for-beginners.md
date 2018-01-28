# Git for Beginners

__What is it?__ Version Control System

__What does it do?__ Helps manage project files

__How?__

- __History__ - Git keeps track of every change that we make
- __Collaboration__ - Everyone in team have access to files
- __Feature branches__ - You can multitask

__Why?__ Industry Standard

## Git vocabulary

**_Repository (Repo)_** = Project

**_Working Directory_** = Location on computer where our project lives

**_Staging_** = Preparing files before saving

**_Commit_** = Saving

**_Clone_** = Copy an existing repository from a server to our computer's hard drive

__Public repo__ charactersized that everyone can __see__ your code but only you can __change__ your code

## Git Command Line Basics

### Setup
`which git` : Shows where Git's binary file is located
`git --version` : Shows which version of Git is installed

`git config -- global user.name "yourusername"` and  `git config -- global user.email "your@email"` : Set a Git username and email

### General

`pwd` : Print Working Directory shows where currently we are

`cd` : Change Directory move us to directory where we want to be

`cd ..` : Goes to directory that is up

`mkdir "new directory name"` : Make Directory makes a new directory

`touch "new file name"` : Creates new file in current directory

`git init` : Initiaizes new repository

`git status` : Shows which files are being modified and which files are ready to be commited

`git add -A` : Adds files to staging area/ Prepares everything before commited

`git commit -m "Message"` : Saves changes with message about changes

`git checkout --.` : Going back to the moment where commit has been made

### Push and Pull

__Git stores data locally on our hard drives__.

__Git is not the same as GitHub__.

__In case our evil cat wants to delete our files or we throwed computer from edge of cliff we have wonderful service that host repository - GitHub__.

If we want to do a commit on GitHub we need to __PUSH__ our changes that we made in Git repo on our computer to GitHub's server repo.

`git push origin master`

If we want to download the latest changes that we have been made, which in some case we don't have, we need to __PULL__ them from repo on GitHub's server to repo on our computer.

`git pull origin master`

`git remote -v` : Shows address where Git thinks you want to push to

`git remote set-url origin address` : Changes url address to where you want to push
