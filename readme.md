# My Git Cheatsheet

## Creating a Git Repo

In the folder you want to create a repo, do the following command in terminal

``` 
git init

```

**Always check that you are not already in a repo by using git status**

## Adding Files to Staging

Staging is files that being tracks to be committed

use git status to see which files are untracked(red) or in staging(green)

```
git status
```

three ways to add files to staging

- add on file at a time `git add <filename>`
- add all files in the repo `git add -A`
- add all files in my current folder with `git add .`


## Committing Files to Our Repo

```
git commit -m "some random text, "something describes what changed"
```
**If you forget the -m, you'll end up in vim, to exit type ":wq"**


## Looking at our commit history

```
git log
```
```
git log --oneline
```

## Working with Remotes (Enterprise, github, gitlab, bitbucket)

- to add a remote 'git remote add <name> <url>'

- to see list of remotes `git remote -v`

- to the push code `git push <remoteName> <branchName>`

- to see your current branch  `git branch`
