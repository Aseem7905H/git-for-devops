# Git and GitHub Commands Guide

1. Initializing a Git Repository:
   git init
   Initializes a new Git repository in the current directory.

2. Checking the Status of Files:
   git status
   Displays the status of changes (staged, unstaged, untracked).

3. Adding Files to the Staging Area:
   git add <file-name>
   git add .
   - Adds a specific file to the staging area.
   - Adds all changes to the staging area.

4. Committing Changes:
   git commit -m "commit message"
   Records changes in the repository with a message.

5. Configuring User Information:
   git config --global user.name "YourName"
   git config --global user.email "YourEmail@example.com"
   Sets your name and email for all repositories.

6. Viewing Commit History:
   git log
   git log --oneline
   - Shows the commit history.
   - Displays a simplified one-line commit history.

7. Creating Branches:
   git branch <branch-name>
   git checkout -b <branch-name>
   git checkout <branch-name>
   - Creates a new branch.
   - Creates and switches to a new branch.
   - Switches to an existing branch.

8. Removing Files from Git:
   git rm --cached <file-name>
   Removes a file from the staging area (keeps it locally).

9. Restoring Changes:
   git restore <file-name>
   Restores a file to the last committed state.

10. Merging Branches:
    git merge <branch-name>
    Merges the specified branch into the current branch.

11. Viewing Branches:
    git branch
    Lists all branches in the repository.

12. Cloning a Repository:
    git clone <repository-url>
    Clones a repository from GitHub to your local machine.

13. Pushing Changes to GitHub:
    git push origin <branch-name>
    Pushes changes to the specified branch on GitHub.

14. Pulling Changes from GitHub:
    git pull origin <branch-name>
    Fetches and merges changes from GitHub.

15. Viewing Remote Repositories:
    git remote -v
    Shows the remote URLs for the repository.
