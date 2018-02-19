# Homework 2 - Michael Barlow
## CSCI 5828 - Spring 2018

***

[create README.md and edit]
git init
git add . && git commit -m "commit 0"

[edit README.md]
git add .&& git commit -m "commit 1"

[edit README.md]
git add . && git commit -m "commit 2"

git checkout [sha for commit 0]
git checkout -b bug-fix
[edit README.md]
git add . && git commit -m "commit 3"

[edit README.md]
git add . && git commit -m "commit 4"

git merge master
[edit README.md, fix merge conflict]
git add . && git commit -m "commit 5"

[edit README.md]
git add . && git commit -m "commit 6"

git checkout [sha for commit 4]
git checkout -b bug-fix-experimental
[edit README.md]
git add . && git commit -m "commit 7"

[edit README.md]
git add . && git commit -m "commit 8"

[edit README.md]
git add . && git commit -m "commit 9"

git checkout master
[edit README.md]
git add . && git commit -m "commit 10"

git checkout bug-fix
git merge bug-fix-experimental
[edit README.md, fix merge conflict]
git add . && git commit -m "commit 11"

[edit README.md]
git add . && git commit -m "commit 12"

git checkout master
git merge bug-fix
[edit README.md, fix merge conflict]
git add . && git commit -m "commit 13"
