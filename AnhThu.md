# Setup

## Set the name and email that will be attached to your commits and tags

$ git config --global user.name "Your name"

$ git config --global user.email "email@gmail.com"

# Starting a Project with Git

## Create a local repo (omit <directory> to initialise the current directory as a git repo)
$ git init <directory>

## Download a remote repo
$ git clone <url>

# Make a Change

## Add a file to staging
$ git add <file>


## Stage all files
$ git add .

## Commit all staged files to git
$ git commit -m "commit message"

## Add all changes made to tracked files & commit
$ git commit -am "commit message"