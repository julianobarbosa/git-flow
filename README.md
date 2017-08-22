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
