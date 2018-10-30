# learnGit

Hey there! So, this project is a part of the GCI'2018 task i did for [**OpenWISP**](https://github.com/openwisp) in which i have to follow this [*course*](https://www.udemy.com/git-expert-4-hours) on *udemy*. Here i will be sharing whatever i learned after completion of the course. I would recommend you to check out the course if you are a beginner and want to get hold of *git* and *github* so that thing would be smooth and easy.

## What is GIT?
**Git** is most popular implementation of a distributed version control system.

## Git Repositories
* It stores full history and thus helping in maintaining different versions of the application.
* It is hosted either locally, or on a shared server.
* Core contributers can make copy of the repository by means of *fork* and then *clone* the forked repository and Update it using *push/pull* system.
* Repository that is stored other than locally is a *Remote Repostitory*.

## Repository VS directory
* *Repositories* are timelines of the entire project including previous changes.
* *Directory* is the working directory of the project at their current state of time.

## SourceTree
**SourceTree** is a *GUI*(Graphical User Interface) based *GIT* allowing us to interact with our repositories through a graphical interface.

## Basic Commands

| Command | Description |
 | ------- | ----------- |
 | `git init` | To initialize a local Git repository |
 | `git status` | To check status |
 | `git clone <url-of-forked-repo>` | To create a copy of a remote repository into your local machine |
 | `git add <file>` | To add the file to the staging area |
 | `git add .` or `git add --all` | To add all the files to the staging area |
 | `git rm -r <file>` | Remove a file completely(staging area as well) |
 | `git rm --cached <file>`| Remove a file from staging area |
 | `git commit -m "your-commit-message"` | To commit your changes |
 | `git log` | To show a list of all the commits |
 | `git checkout` | Go back and revert changes also, if needed move btw branches |
 | `git checkout <commit-hash>` | To detach head to a prev commit |
 | `git checkout master` | To move to master branch |
 | `git checkout -b <branch-name>` | To make a new branch and switch to it |
 | `git revert <commit-hash>` | To revert the changes permanently |
 | `git reset --hard <commit-hash>` | To reset commits not pushed |
 | `git remote -v` | To show all of your remote origins |
 | `git push` | To push changes after commiting |
 | `git pull` or `git pull <remote> <branch>`> | To Update our local repo with all the information |
 
  
 