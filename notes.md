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

## Remote Workflow
git push = send local commits to GitHub.
git fetch = get information about new remote commits without changing local files.
get pull = get remote changes and update the current local branch.

## Pull Request Workflow

1. Create and switch to a feature branch.
2. Make changes and create a commit.
3. Push the feature branch to GitHub.
4. create a Pull Request from the feature branch into main. 
5. Review the changed files.
6. Merge the Pull Request on GitHub.
7. Switch to the local main branch.
8. Fetch remote updates.
9. Pull the changes into the local main branch.
10. Verify that the local and remote branches are synchronized.