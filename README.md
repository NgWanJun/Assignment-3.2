# 3.2 Assignment

## What is Github Authentication, and how can we implement it?

Github Authentication is the process of verifying the identity of a user who is trying to access a Github repository or perform any other action that requires authentication.

One way of implementing greater authentication is to implement Two-Factor Authentication (2FA). We can use an authenticator app or send the 2FA code via SMS as an extra layer of security. 

Another way is to use SSH keys. We can create a secure key pair that can be used for remote authentication to a Github repository or account. 

## 15 Github Commands and their usages

1. `git init` initialises a new Git repository. It creates a new '.git' directory in the current directory and sets up the necessary files and data structure to begin tracking changes.

2. `git clone` creates a copy of an existing Git repository. It downloads the entire repository and sets up a local copy on your machine.

3. `git add` adds changes to the staging area. You use this command before committing changes to the repository.

4. `git commit` creates a new commit with changes that have been added to the staging area. 

5. `git push` sends the committed changes to the remote repository. It updates the remote repository with your local changes.

6. `git pull` fetches changes from the remote repository and merges them into your local repository.

7. `git status` shows the current status of the repository. It displays which files have been modified, staged for next commit and which files are untracked.

8. `git log` shows the commit history of the repository. 

9. `git branch` shows the list of branches in the repository. 

10. `git checkout` switches to a different branch. You can use it to move between different branches or create new ones.

11. `git merge` merges changes from 1 branch to another. 

12. `git stash` temporarily saves changes that are not yet ready to be committed. It allows you to switch branches without losing changes.

13. `git reset` resets the changes made in the repository. You can use it to unstage changes or reset changes to a previous commit.

14. `git fetch` fetches changes from the remote repository without merging them into your local repository.

15. `git remote` shows the list of remote repositories associated with your local repository. It displays the URL of each remote repository. 


## What are the 4 Github Commands that one will likely use the most in a real project?

1. `git add` to add changes to the staging area.

2. `git push` to push changes to remote repository from local machine.

3. `git pull` to pull changes made by other collaborators to the remote repository.

4. `git commit` to commit changes to the local repository. 