# git-practice
Dummy repo to practice or test git stuff


## Creating a new branch

_NOTE: use `upstream` instead of `origin` if forked_ 

```bash
git fetch origin

git checkout origin/master

git checkout -b "new-feature-name"
```

## Rebase to get updates from origin

```bash
git fetch origin

git rebase -i origin/master

git push origin "feature-branch-name" -f

```

## Git Stashing

### To list stashes
```bash
git stash list
```

### To apply specific stash
```bash
git stash apply stash@{0}
```

### To drop specific stash
```bash
git stash drop stash@{0}
```

