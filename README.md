![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)  [![Open Source Love](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.md)                                                    



<p align="center">
    <img src="Images/git-logo.png" alt="Logo" height="60">
<h3 align="center">Git-Cheatsheet</h3></p>

---

Created by: <img src="Images/gdg-logo-trans.png" alt="GDG-LOGO" width="32px">  <b>GDG Siliguri Open-Source Community</b>

<p><br /></p>

## What is Git? :thinking::syringe:



Git is a version-control tool by which you can work in any project with teams and it will store the history and checkpoints of all the changes you are making in that project. So if you are facing any issue in current version of your project, using Git you can restore to previous stable version. Git is an essential tool for open-source contribution and any development area. :pill:

<br>

## How to Install Git? :inbox_tray::computer:

* **Git for Windows and Mac:**

  -Go to [Git-SCM](https://git-scm.com/) :beginner:

  -Go to Downloads

  -Download for windows or mac whichever os you are using

  -Install that downloaded file

  

* **Git for Debian, Ubuntu and Mint:**

  -In terminal type the following commands

  ```
  # sudo apt update
  # sudo apt install git
  ```


* **Git for RHEL, CentOS and Frdora:**

  -In terminal type the following commands

  ```
  # sudo yum update
  # sudo yum install git
  ```


* **Git for Arch:**

  -In terminal type the following commands

  ```
  # sudo pacman -S git
  ```

<br>

## Check git version :rocket:

Use the following command in the bash or terminal.

```
git --version
```

<br>

## Configuration :wrench:

Use the following command to configure email and username.

```
git config --global user.email "<YOUR MAIL HERE>"
git config --global user.name "<YOUR USERNAME HERE>"
```

Use the following command to check other configurations.

```
git config --list
git config <SELECT A SPECIFIC CONFIGURATION FROM LIST LIKE "user.email">
```

Use the following command to set a specific configuration.

```
git config --global <SELECT A SPECIFIC CONFIGURATION FROM LIST LIKE "user.email"> <VALUE>
```

<br>

## Some commands for Bash/Command Line:ledger:

Check present directory

```
pwd
```

Go to parent directory

```
cd ~
```

Go to backward directory

```
cd ..
```

See lists of files inside a directory

```
ls
```

Go to a directory

```
cd <FOLDER NAME>
```

Clear everything on screen

```
clear
```

Create file

```
touch <FILENAME.EXTENSION>
```

Delete files

```
git rm <FILENAME.EXTENSION>
```

Rename files

```
git mv <PREVIOUS-NAME.EXTENSION> <NEW-FILENAME.EXTENSION>
```

Move files

```
git mv <FILENAME.EXTENSION> <DIRECTORY-NAME>/<FILENAME.EXTENSION>
git mv <PREVIOUS-FILENAME.EXTENSION> <DIRECTORY-NAME>/<NEW-FILENAME.EXTENSION>
```

<br>

## Initializing Git :page_with_curl:

```
git init
```

<br>

## Checking untracked files:round_pushpin:

```
git status
```

<br>

## Adding changes (Working area to staging area):space_invader:

```
git add <FILENAME.EXTENTION> (for specific file)
git add .                    (for all files)
git add "*.<EXTENSION>"      (for adding all simmilar file)
```

<br>

## Committing files:bookmark_tabs:

```
git commit -m "<MESSAGE>"   (staging area to repository)
git commit -am "<MESSAGE>"  (working copy to repository to avoid adding)
```

<br>

## Checking commit history:partly_sunny:

```
git log
git log --author="<AUTHOR NAME>" (for checking commits of specific author)
```

<br>

## Watching difference between:zap:

```
git diff          (repository to working copy)
git diff --staged (repository to staging area)
```

<br>

## Undo:pushpin::arrows_clockwise:

```
git checkout --<FILENAME.EXTENSION>        (repository to working copy)
git reset HEAD <FILENAME.EXTENSION>        (staging area to working copy)
git checkout <HASH> --<FILENAME.EXTENSION> (get older version)
```

<br>

## Remote repository:mega::bell:

```
git remote add <NICKNAME> <URL OF YOUR GIT REPOSITORY>
git remote
git remote remove <NICKNAME>
git remote rename <OLD-NICKNAME> <NEW-NICKNAME>
```

<br>

## Clone, Pull, Push:sunrise_over_mountains:

```
git clone <URL OF GIT REPOSITORY> (cloning repo, add .git after the link if you want to get the histories of all commits)

git pull <NICKNAME> master        (you can replace master with other branchname)

git push -u <NICKNAME> master     (you can replace master with other branchname)
```

<br>

## Branch:world_map:

Create branch

```
git branch <BRANCH-NAME>
```

Go to another branch

```
git checkout branchName
```

View all branches 

```
git branch
```

Merge branchs

```
git branch branchName
```

Delete branch 

```
git branch -d branchName
```



<br><br>

See CONTRIBUTING.md for contributions. :boom:
