---
title: View merged branches
type: snippet
language: git
tags: [repository,branch]
cover: cobbled-street
dateModified: 2021-04-13
---

Prints a list of all merged local branches.

- Use `git branch -a --merged` to display a list of all merged local branches.
- Use arrow keys to navigate, press <kbd>Q</kbd> to exit.

```shell
git branch -a --merged

# Examples
git checkout master
git branch -a --merged
# patch-1
# patch-2
```
