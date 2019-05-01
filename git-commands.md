## Git commands

`git add .`
Add all

`git add new-folder/test-file-1.md`
Add a particular file or directory

`git commit -m`
Add a commit message

`git pull origin branch-name`
Pull down the lastest changes to your branch

`git push origin branch-name`
Push your changes

`git rm test-file-1.md`
Remove the file _test-file-1.md_ from the directory you’re in

`git commit --amend`
Amend your last commit

`git rebase -i HEAD~3`
Perform an interactive rebase – get the last 3 commits

`git stash`
Stash your local changes

`git stash apply`
Apply the local changes you’ve stashed

`git checkout -b new-branch-name`
Create a new git branch and check it out

`git branch -m old-branch-name new-branch-name` (alias to `git branch --move`)
Rename a branch locally

`git push origin -u new-branch-name` (alias of `git push origin --set-upstream`)
Set upstream

`git push origin --delete old-branch-name`
Delete an old remote branch

`git branch -d branch-name`
Delete local branch
