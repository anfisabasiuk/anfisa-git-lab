# Git Notes

## The Four Places

### 1. Working Directory
Files I am currently editing in VS Code.
After I change and save a file, the changes are in the Working Directory.

### 2. Staging Area
Changes selected for th enext commit.
Command: git add <file>

### 3. Local Repository
Commt history stored on my computer.
Command: git commit -m "message"

### 4. Remote Repository
Commit history stored remotely on GitHub.
Command: git push

## Basic Git Workflow
Change file
- git status
- git add <file>
- git status
- git commit -m "message"
- git status
- git push
- git status

## Important Terms
main = my local main branch
origin = the name of the connected remote repository
origin/main = my local Git's information about the remote main branch

Before push:
main can be ahead of origin/main

After push:
main and origin/main are synchronized

## Branch Workflow
Create and switch to a new branch
Command: git switch -c <branch-name>

Make changes and create a commit:
git status
git add <file>
git commit -m "message"

Switch back to main
Command: git switch main

Merge the branch into main
Command: git merge <branch-name>

Push main to GitHub
Command: git push

Delete the merged local branch
Command: git branch -d <branch-name>