# Introduction to Git and GitHub

The repository contains the summary of _Shahzad's ([@shaizCodes](https://github.com/shaizCodes))_ Git and GitHub session.

## Summary

| Git Command | Description |
|-------------|-------------|
| [`git init`](#init)  | initializes an empty Git repository |
| [`git status`](#status) | prints the status of repository working tree and staging area |
| [`git add <file>`](#add) | stages the space-separated files of working tree |
| [`git commit -m "commit title" -m "commit description"`](#commit) | commits the staged files into a snapshot |
| [`git remote show`](#remote) | lists remote servers if any |
| [`git remote add`](#remote) | defines a remote server |
| [`git push`](#push) | sends local repository changes to remote repository |

## Screenshots

- ### init

  - > ![`git init` initializes empty repository](./ScreenShots/init.png)

- ### status

  - > ![`git status` prints repository status](./ScreenShots/status.png)

- ### add

  - > ![`git add .\README .\ScreenShots\`](./ScreenShots/add.png)

- ### commit

  - > ![`git commit -m "initial commit" -m "introduce repository and a few git commands"`](./ScreenShots/commit.png)
  - > ![`git commit --amend -m "initial commit" -m "introduce repository and a few git commands"`](./ScreenShots/commit-amend.png)

- ### remote

  - > ![`git remote show` lists the remote servers](./ScreenShots/remote-show.png)
  - > ![`git remote add` defines a remote server](./ScreenShots/remote-add.png)

- ### push

  - > !['git push' sends local repository changes to remote repository](./ScreenShots/push.png)

- ### rm

  - > !['git rm --cached <file>' removes file cache/history from staging area](./ScreenShots/rm-cached.png)
