Git Commands by Stages
1. Initializing a Repository
git init

Initializes a new Git repository in the current directory.

3. Viewing Files and Status
ls -a
Lists all files, including hidden files (those starting with a dot).

git status
Displays the state of the working directory and the staging area, showing which files are staged, unstaged, or untracked.

3. Creating and Removing Files
4. 
touch madhu.txt swarna.txt
Creates empty files named madhu.txt and swarna.txt if they do not exist, or updates their timestamps if they do.

rm maddy.txt
Removes (deletes) the file maddy.txt.

4. Staging Changes
bash
Copy code
git add swarna.txt
Stages the file swarna.txt for the next commit.

bash
Copy code
git rm --cached madhu.txt
Removes madhu.txt from the staging area without deleting the actual file.

5. Committing Changes
bash
Copy code
git commit madhu.txt swarna.txt
Commits the changes to madhu.txt and swarna.txt to the repository.

bash
Copy code
git commit -m "commit message"
Commits staged changes to the repository with a message describing the commit.

6. Configuring User Information
bash
Copy code
git config --global user.name "name"
Sets the global Git username for commits.

bash
Copy code
git config --global user.email "email@example.com"
Sets the global Git email for commits.

7. Viewing Commit History
bash
Copy code
git log
Displays the commit history of the current branch.

8. Exiting the Session
bash
Copy code
exit
