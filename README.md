# git-flow
## Install Manual
wget --no-check-certificate -q  https://raw.githubusercontent.com/petervanderdoes/gitflow-avh/develop/contrib/gitflow-installer.sh && sudo bash gitflow-installer.sh install develop; rm gitflow-installer.sh

## Install using apt command (Ubuntu)
sudo apt install git-flow
git-flow samples


## Initial flow
git flow init

## Push
git push origin --all

## Create a Feature
git flow feature start pointless-comments

## Finish a Feature
git flow feature finish pointless_comments
