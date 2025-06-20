# Git Commands Reference with Explanations
This document contains essential Git commands categorized by topic, along with brief explanations.

# 1. Setup & Configuration
Set your Git username:
`git config --global user.name "iam-madhukar"`

Sets your global Git username used in commits.

Set your Git email:
`git config --global user.email "madhukar1ramesh@gmail.com"`

Sets your global Git email used in commits.

# 2. Initialize Repository
Create a new project folder:
`mkdir git-for-devops`
Creates a directory named `git-for-devops`.

Navigate into the project directory:
`cd git-for-devops`
Changes current directory to `git-for-devops`.

Initialize the Git repository:
`git init`
Starts a new Git repository in the current folder.

# 3. File Operations
Create new files:
`touch python.txt java.txt`
Creates two empty files.

`touch go.txt`
Creates an empty file named `go.txt`.

Edit a file:
`vim java.txt`
Opens `java.txt` in Vim for editing.

View contents and location:
`ls`
Lists files in the current directory.

`pwd`
Shows the full path of the current working directory.


# 4. Git Status
`git status`
Displays the state of the working directory and staging area.

# 5. Staging and Committing Files
Add files to staging:
`git add python.txt java.txt`
Stages the two newly created files.

`git add java.txt`
Stages changes made to `java.txt`.

`git add go.txt`
Stages the `go.txt` file.

`git add python.txt`
Re-adds `python.txt` after removing from tracking.

Commit changes:
`git commit -m "add python java"`
Commits staged files with a message.

`git commit -m "modified java file"`
Commits changes to `java.txt`.

`git commit -m "added go"`
Commits the `go.txt` file.

`git commit -m "added python file"`
Commits the `python.txt` file.

# 6. Removing Files
`git rm --cached python.txt`
Stops tracking `python.txt` but leaves it on disk.

# 7. Restoring Files
`git restore python.txt`
Restores `python.txt` to the last committed version.

# 8. Branching
List branches:
`git branch`
Shows all local branches.

Create and switch to new branches:
`git checkout -b dev`
Creates and switches to a branch named dev.

`git checkout -b from-dev`
Creates and switches to a branch from the current state.

`git checkout -b from-master`
Creates a branch from the master branch.

Switch between branches:
`git checkout dev`
Switches to the dev branch.

`git checkout master`
Switches back to the master branch.


# 9. Viewing Logs
`git log`
Shows full commit history.

`git log --oneline`
Displays a simplified version of the commit log.

# 10. Navigating Directories
`cd git-for-devops`
Enters the project directory.

`cd ..`
Moves up one directory level.

# 11. Other commands
`git branch -d <branch>` – Deletes a local branch.

`git merge <branch>` – Merges a branch into the current one.

`git diff` – Shows file differences not yet staged.

git stash – Temporarily saves changes not yet committed.
