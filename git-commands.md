# Git commands

## Add

`git add .`
Add all

`git add new-folder/test-file-1.md`
Add a particular file or directory

## Remove

`git rm test-file-1.md`
Remove the file _test-file-1.md_ from the directory you’re in

## Commit

`git commit -m`
Add a commit message

`git commit --amend`
Amend your last commit

## Branch

`git checkout -b new-branch-name`
Create a new git branch and check it out

`git branch -m old-branch-name new-branch-name` (alias to `git branch --move`)
Rename a branch locally

`git branch -d branch-name`
Delete local branch

## Pull

`git pull origin branch-name`
Pull down the lastest changes to your branch

## Push

`git push origin branch-name`
Push your changes

`git push origin -u new-branch-name` (alias of `git push origin --set-upstream`)
Set upstream

`git push origin --delete old-branch-name`
Delete an old remote branch

`git push --force`
Perform a force-push. _Do not_ do this on a public or shared branch.

## Rebase

`git rebase branch-name`
Perform a rebase – move

`git rebase -i HEAD~3`
Perform an interactive rebase – get the last 3 commits

## Revert

The `revert` command adds a new commit showing the revert.

`git revert HEAD`
Reverts the last commit

`git revert 1061e79`
Reverts the specified commit

## Stash

`git stash`
Stash your local changes

`git stash -u`
Stash local changes, including untracked files – files that have not been staged, or are ignored

`git stash apply`
Apply the local changes you’ve stashed to your current working (without removing from the stash)

`git stash list`
List your stashes

`git stash save 'my message'`
Save your stash with a message (default is 'WIP' + branch and commit the stash was created from)

`git stash pop`
Reapply the last stash to your current working branch (removing them from the stash)

`git stash pop stash@{2}`
Reapply a specific stash and remove from the stash list

`git stash -p` (alias of `git stash --patch`)
Iterate through your changes (or hunks) and save them individually

`git stash branch branch-name stash@{1}`
Create a branch from your stash

`git stash drop stash@{1}`
Delete a stash

`git stash clear`
Clear all your stashes

## Discard

`git reset --hard`
Discard your local changes without saving them
