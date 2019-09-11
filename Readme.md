# Readme.md

This is my fit cheat sheet

# git commands
```bash

git init REPO-NAME
```

```bash
git status
show the status of the git repository
```

```bash
git show 
```
---show s the commit history and changes 

```bash
git commit -m "message"
```
commits the stashed files to the repo, and adds the message that describes what was done

- creates a repository called REPO-NAME

other Git things 

**.gitignore** is a file that tells git  files/folders that are not to ve part of the repository

THis line will be detelted next

```bash
git log 
````
show a history of the commits made to this point in time

```bash
git log --all --decorate --oneline --graph
```
-display a graph of commits, one commit per line

```bash 
git config --global alias.adog "log --all --decorate --oneline --graph
```
- creats a git alias for the log all decorate oneline graph 
- use this alias by git adog