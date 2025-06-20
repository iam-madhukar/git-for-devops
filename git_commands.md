# Git Commands Reference with Explanations

This document contains essential Git commands categorized by topic, along with brief explanations.

---

## 1. Setup & Configuration

```bash
git config --global user.name "iam-madhukar"
Sets your global Git username (used in commits).

bash
Copy
Edit
git config --global user.email "madhukar1ramesh@gmail.com"
Sets your global Git email (used in commits).

2. Initialize Repository
bash
Copy
Edit
mkdir git-for-devops
Creates a new directory named git-for-devops.

bash
Copy
Edit
cd git-for-devops
Navigates into the git-for-devops directory.

bash
Copy
Edit
git init
Initializes a new Git repository in the current directory.

3. File Operations
bash
Copy
Edit
touch python.txt java.txt
Creates two new empty files: python.txt and java.txt.

bash
Copy
Edit
vim java.txt
Opens java.txt in Vim editor for editing.

bash
Copy
Edit
touch go.txt
Creates a new empty file go.txt.

bash
Copy
Edit
ls
Lists files in the current directory.

bash
Copy
Edit
pwd
Shows the full path of the current directory.

bash
Copy
Edit
clear
Clears the terminal screen for readability.

4. Git Status
bash
Copy
Edit
git status
Shows the current state of the working directory and staging area.

5. Staging and Committing Files
bash
Copy
Edit
git add python.txt java.txt
Stages python.txt and java.txt for commit.

bash
Copy
Edit
git commit -m "add python java"
Commits staged files with the message "add python java".

bash
Copy
Edit
git add java.txt
Stages the modified java.txt file for commit.

bash
Copy
Edit
git commit -m "modified java file"
Commits the change to java.txt with a message.

bash
Copy
Edit
git add go.txt
Stages go.txt for commit.

bash
Copy
Edit
git commit -m "added go"
Commits go.txt with a descriptive message.

bash
Copy
Edit
git add python.txt
Re-stages python.txt after previous untracking.

bash
Copy
Edit
git commit -m "added python file"
Commits the staged python.txt with a message.

6. Removing Files
bash
Copy
Edit
git rm --cached python.txt
Unstages and stops tracking python.txt, but keeps it in the working directory.

7. Restoring Files
bash
Copy
Edit
git restore python.txt
Reverts changes made to python.txt, restoring it to the last committed state.

8. Branching
bash
Copy
Edit
git branch
Lists all local branches in the repository.

bash
Copy
Edit
git checkout -b dev
Creates and switches to a new branch named dev.

bash
Copy
Edit
git checkout dev
Switches to the dev branch.

bash
Copy
Edit
git checkout master
Switches back to the master branch.

bash
Copy
Edit
git checkout -b from-dev
Creates and switches to a new branch from-dev from the current branch.

bash
Copy
Edit
git checkout -b from-master
Creates and switches to a new branch from-master from the current branch.

9. Viewing Logs
bash
Copy
Edit
git log
Displays the full commit history with detailed information.

bash
Copy
Edit
git log --oneline
Shows a simplified, one-line-per-commit log.

10. Navigating Directories (Shell Commands)
bash
Copy
Edit
cd git-for-devops
Navigates into the project directory (again if needed).

bash
Copy
Edit
cd ..
Moves up one directory level.
