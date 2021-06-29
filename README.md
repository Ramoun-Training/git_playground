# Git Playground

a play ground for learning git.

## basic commands

```bash
git commit -m "First"
git commit -m "Second"
git commit -m "Third"

git log --oneline

git branch
git branch my-feature
git branch

git checkout my-feature
git branch
git log --oneline

git commit -m "Fourth"
git commit -m "Fifth"
git log --oneline

git checkout main
git log --oneline

git branch my-second-feature
git commit -m "Sixth"
git commit -m "Seventh"
git log --oneline

git checkout my-feature
git branch bug-fix
git branch

git commit -m "Eighth"
git commit -m "Ninth"
git log --oneline

git checkout bug-fix
git commit -m "Tenth commit"
git log --oneline

git checkout my-feature
git log --oneline

git merge bug-fix
git checkout my-feature
git log --oneline
git commit -m "Eleventh commit"
git log --oneline

git checkout master
git log --oneline

git merge my-feature
git log --oneline
```

## Notes

`log` gets log of current branch only.

## Visualization

- [Github Git School](http://git-school.github.io/visualizing-git/)