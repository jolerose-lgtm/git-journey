git init - initialize
git status - to check for changes or modification
git add, git add --all, git add -A - stage every single change across the entire project
git add . - stage changes within the current directory you are in
git --version - to check if git is properly installed
git reset - remove from staging area to working directory
git add * - stages only new and modified files but not deleted files
git reset HEAD - undo commit and return to working directory
git rm - deleting a file and staging it simultaneously
git reset --hard - restore changes and deleted files
git rm -f - force deletion of a file
git rm --cached - remove from staging area but keeps it physically in the working directory
git rm -r (folder) - if the folder contains subfolders or files all of them will be removed recursively
git log - view commits
git log --one line - short summary of commits
git branch - shows lists of all branches
git branch (name) - create another branch
git checkout - move to another branch
git merge -m (branch) - Merging
git diff - to check differences or change between commits
git push - send local changes to remote repository
git fetch - send remote changes to local repository but not merging them yet
git pull - fetching and merging
git restore . - restore last committed version
git stash - set aside a branch temporaririly
git stash list - list of saved stashed changes
git stash pop - reappear stashed changes and remove from list
git stash apply - reappear stashed changes and remains in the list to be used later
git revert - undo changes made in a previous commit but instead of deleting the old commit it creates a new commit that brings back the project to its previous state


