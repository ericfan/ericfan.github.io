---
layout: post
title: Git Useful Command
categories: Git
description: Useful command when using git
keywords: git
---
## Create a new branch same as another repository
```
git remote add fork <url of fork>
git fetch fork
git checkout -b fork_branch fork/<branch>
git push origin fork_branch
```
