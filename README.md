# git-flow
## Install Manual
```console
wget --no-check-certificate -q https://raw.githubusercontent.com/petervanderdoes/gitflow-avh/develop/contrib/gitflow-installer.sh && sudo bash gitflow-installer.sh install develop; rm gitflow-installer.sh
```

## Install using apt command (Ubuntu)
```console
sudo apt install git-flow
```

## Initial flow
```console
git flow init
```

## Push
```console
git push origin --all
```

## Create a Feature
```console
git flow feature start pointless-comments
```

## Finish a Feature
```console
git flow feature finish pointless_comments
```
