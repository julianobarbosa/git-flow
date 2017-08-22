# git-flow
## Install Manual
```console
wget --no-check-certificate -q https://raw.githubusercontent.com/petervanderdoes/gitflow-avh/develop/contrib/gitflow-installer.sh && sudo bash gitflow-installer.sh install develop; rm gitflow-installer.sh
```

## Install using apt command (Ubuntu)
```console
sudo apt install git-flow
```

## Flow: Initial
```console
git flow init
```

## Flow: Push
```console
git push origin --all
```

## Feature: Create
```console
git flow feature start pointless-comments
```

## Feature: Push
```console
git push --set-upstream origin feature/pointless-comments
```

## Feature: Finish
```console
git flow feature finish pointless_comments
```

## Feature to Develop
```console
git push --set-upstream origin develop
```

## Release: Start
```console
git flow release start 1.0.1
```

## sequence
```console
git flow init
git push origin --all
git flow feature start pointless-comments
vim README.md
git add .
git commit -a
git status
git push --set-upstream origin feature/pointless-comments
vim README.md
git add .
git commit -a
git push --set-upstream origin feature/pointless-comments
vim README.md
git add .
git commit -a
git push --set-upstream origin feature/pointless-comments
vim README.md
git add .
git commit -a
git push --set-upstream origin feature/pointless-comments
git flow feature finish
git push --set-upstream origin develop
git flow release start 1.0.1
```
