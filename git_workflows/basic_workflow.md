# Basic Git WorkFlow

## Setup

```bash
mkdir directory
cd directory

# create a new repo on github
git init

# first commit
echo "# www" >> README.md
git add README.md
git commit -m "first commit"

# push to remote repo
git branch -M main
git remote add origin git@github.com:MrRamoun/www.git
git push -u origin main

# using git flow
git flow init

# set develop branch
git checkout develop
git push origin develop

# create a new feature for develop
git flow feature start new-feature
git push origin new-feature

# create a new bug-fix for the feature
git flow bugfix start my-bugfix
git push origin my-bugfix

# mereg my bug-fix
git checkout new-feature
git merge bug-fix
git push origin my-bugfix

# back to new-feature branch
git checkout new-feature

# log
git log --oneline
```
