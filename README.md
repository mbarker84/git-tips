# git-tips

A little repository for testing and demo-ing git commands and shortcuts

---

## General commands

`mkdir new-folder`
Create a new directory

`cd new-folder`
Move into that directory

`touch test-file-1.md`
Create a new file in the directory you’re in called _test-file-1.md_

`touch test-file-1.md test-file-2.md`
Create a multiple files in the directory you’re in by separating them with a space

`ls`
List the contents of the directory you’re in

`ls -l test-file-1.md`
Show details of a particular file

`cat > test-file-2.md`
Create a new file and immediately start editing that file in the terminal. Press `ctrl + D` to save and exit

`mv`
Rename

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
