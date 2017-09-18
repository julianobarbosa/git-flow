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

## Release: Finish
```console
git flow release finish 1.0.1
```

## Release: Push
```console
git push --set-upstream origin release/1.0.1
```

## Released:
```console
git checkout master
git push origin --all --follow-tags
```


## git: Log format
```console
git log --pretty=format:"%h %an %ar - %s"
```
e530db3 Scrapbook Git Tutorial 9 minutes ago - [# 3] - Step 3 - Git A
dd

7e597ef Scrapbook Git Tutorial 13 minutes ago - Initial Commit
## git: Show
```console
git show 7e597ef
```

```console
commit 7e597ef90f3f46fd7b68feaae6890636b8a52d28
Author: Scrapbook Git Tutorial <git-tutorial@joinscrapbook.com>
Date:   Mon Sep 18 12:17:50 2017 +0000

    Initial Commit

diff --git a/committed.js b/committed.js
new file mode 100644
index 0000000..12e7e7c
--- /dev/null
+++ b/committed.js
@@ -0,0 +1 @@
+console.log("Committed File")

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
