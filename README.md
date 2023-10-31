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
    - `git reset --<soft/soft> <HASH>`: do reset with reference to a commit hash

7. Revert
    - `git revert <HASH>`: undo the change in the code that are part of the commit <HASH> and make a new commit


