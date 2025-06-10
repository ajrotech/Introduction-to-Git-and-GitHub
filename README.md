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
| [`git remote add <repo-URL>`](#remote) | defines a remote server |
| [`git rm --cached <file>`](#rm) | removes the file from staging area not from working directory |
| [`git rm -f <file>`](#rm-f) | forcefully removes the file from working directory |
| [`git mv <source-file> <target-file>`](#mv) | moves or renames the source file to the target path or file |
| [`git branch`](#branch) | lists the local branches of the repository |
| [`git branch --all`](#branch) | lists all the branches of repository including remote |
| [`git branch <branch-name>`](#branch) | creates a new branch in current repository |
| [`git checkout <target-branch-name>`](#checkout) | activates the target branch |

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

   - > !['git rm cached' removes the cache file from staging area](./ScreenShots/rm-cached.png)
     
 - ### rm-f
     
  - > !['git rm -f' forcefully removes the cache file from working directory](./ScreenShots/rm-f.png)
    

- ### mv

   - > !['git mv <file> <file>' renames the file](./ScreenShots/mv.png)

- ### branch

   - > !['git branch' lists branches of the local repository](./ScreenShots/branch.png)
   - > !['git branch' lists branches of the local repository](./ScreenShots/branch-all.png)
   - > !['git branch <branch-name>' creates a new branch by the name <branch-name>](./ScreenShots/branch-new.png)

- ### checkout

   - > !['git checkout <branch-name>' activates a branch named <branch-name>](./ScreenShots/checkout-branch.png)
