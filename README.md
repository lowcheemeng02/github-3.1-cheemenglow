# Git Commands

1. Add
    - `git add .`: add all new files
    - `git add xxx.txt`: add only xxx.txt
    - `git add *.txt`: add all .txt files

2. Commit
    - `git commit -m "some message"`: commit the staged changes with a message

3. Push
    - `git push <remote> <local branch>`: push <local branch> to <remote> repository
    - `git push -all <remote>`: push all local branches to remote

4. Branching
    - `git branch`: list all local branches
    - `git branch -r`: list remote branches
    - `git checkout -b <new_branch>`: create a new branch
    - `git checkout <existing_branch>`: checkout an existing branch

5. Rebase
    - `git rebase -i HEAD~N`: look back on N commits and perform operations such as squash, fixup
    - `git rebase <another_branch>`: rebase current branch onto <another_branch>

6. Reset
    - `git reset --soft HEAD~N`: undo the last N commits while keeping the changes in the files
    - `git reset --hard HEAD~N`: undo the last N commits and don't keep the changes in the files
    - `git reset --<soft/hard> <HASH>`: do reset with reference to a commit hash

7. Revert
    - `git revert <HASH>`: undo the change in the code that are part of the commit <HASH> and make a new commit

8. Merge
    - `git merge <another_br>`: merge <another_br> onto the current branch

9. Log
    - `git log`: view logs
    - `git log --online`: view logs in concise way

10. Cherry-pick
    - `git cherry pick <hash>`: pick <hash> and apply the changes to the current branch

11. Clone
    - `git clone <link>`: clone a repo

12. Stash
    - `git stash`: save uncommitted changes in current branch into a stash to be applied later
    - `git stash apply`: re-apply the stashed changes to the current branch

13. Remote
    - `git remote -v`: view details of remote
    - `git remote add <remote name> <url>`: add a new remote
    - `git remote set-url <remote_name> <new_url>`: change the link of an existing remote
    - `git remote remove <remote_name>`: remove remote

14. Init
    - `git init`: start tracking the files in a folder

15. Pull
    - `git pull`: pull the changes from the remote to the local branch

# Most often used commands

`git add`, `git commit`, `git push`, `git pull`, and also `git merge` are most often used. These are the basic commands when working with changes in the local and remote branches

# What is GitHub Authentication

This is 2FA authentication is a two layer security measure for logging in to Github. The first layer requires the user to log in using the username and password. The second layer requires the user to get an authorisation code from a mobile app.
