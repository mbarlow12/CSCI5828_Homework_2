# Homework 2 - Michael Barlow
## CSCI 5828 - Spring 2018

***

[create README.md and edit]<br>
git init<br>
git add . && git commit -m "commit 0"<br>

[edit README.md]<br>
git add .&& git commit -m "commit 1"<br>

[edit README.md]<br>
git add . && git commit -m "commit 2"<br>

git checkout [sha for commit 0]<br>
git checkout -b bug-fix<br>
[edit README.md]<br>
git add . && git commit -m "commit 3"<br>

[edit README.md]<br>
git add . && git commit -m "commit 4"<br>

git merge master<br>
[edit README.md, fix merge conflict]<br>
git add . && git commit -m "commit 5"<br>

[edit README.md]<br>
git add . && git commit -m "commit 6"<br>

git checkout [sha for commit 4]<br>
git checkout -b bug-fix-experimental<br>
[edit README.md]<br>
git add . && git commit -m "commit 7"<br>

[edit README.md]<br>
git add . && git commit -m "commit 8"<br>

[edit README.md]<br>
git add . && git commit -m "commit 9"<br>

git checkout master<br>
[edit README.md]<br>
git add . && git commit -m "commit 10"<br>

git checkout bug-fix<br>
git merge bug-fix-experimental<br>
[edit README.md, fix merge conflict]<br>
git add . && git commit -m "commit 11"<br>

[edit README.md]<br>
git add . && git commit -m "commit 12"<br>

git checkout master<br>
git merge bug-fix<br>
[edit README.md, fix merge conflict]<br>
git add . && git commit -m "commit 13"<br>

[edit README.md]<br>
git add . && git commit -m "add br tags, add commit graph png, commit 14"<br>
