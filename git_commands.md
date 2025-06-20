# Git Commands Reference with Explanations

This document contains essential Git commands categorized by topic, along with brief explanations.

---

## 1. Setup & Configuration

```bash
git config --global user.name "iam-madhukar"
Sets your global Git username (used in commits).


git config --global user.email "madhukar1ramesh@gmail.com"
Sets your global Git email (used in commits).

## 2. Initialize Repository

mkdir git-for-devops
Creates a new directory named git-for-devops.


cd git-for-devops
Navigates into the git-for-devops directory.


git init
Initializes a new Git repository in the current directory.

## 3. File Operations

touch python.txt java.txt
Creates two new empty files: python.txt and java.txt.


vim java.txt
Opens java.txt in Vim editor for editing.


touch go.txt
Creates a new empty file go.txt.


ls
Lists files in the current directory.


pwd
Shows the full path of the current directory.


clear
Clears the terminal screen for readability.

## 4. Git Status

git status
Shows the current state of the working directory and staging area.

## 5. Staging and Committing Files

git add python.txt java.txt
Stages python.txt and java.txt for commit.


git commit -m "add python java"
Commits staged files with the message "add python java".


git add java.txt
Stages the modified java.txt file for commit.


git commit -m "modified java file"
Commits the change to java.txt with a message.


git add go.txt
Stages go.txt for commit.


git commit -m "added go"
Commits go.txt with a descriptive message.


git add python.txt
Re-stages python.txt after previous untracking.


git commit -m "added python file"
Commits the staged python.txt with a message.

## 6. Removing Files

git rm --cached python.txt
Unstages and stops tracking python.txt, but keeps it in the working directory.

## 7. Restoring Files

git restore python.txt
Reverts changes made to python.txt, restoring it to the last committed state.

## 8. Branching

git branch
Lists all local branches in the repository.


git checkout -b dev
Creates and switches to a new branch named dev.


git checkout dev
Switches to the dev branch.


git checkout master
Switches back to the master branch.


git checkout -b from-dev
Creates and switches to a new branch from-dev from the current branch.


git checkout -b from-master
Creates and switches to a new branch from-master from the current branch.

## 9. Viewing Logs

git log
Displays the full commit history with detailed information.

git log --oneline
Shows a simplified, one-line-per-commit log.

## 10. Navigating Directories (Shell Commands)

cd git-for-devops
Navigates into the project directory (again if needed).

bash
Copy
Edit
cd ..
Moves up one directory level.
