![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)  [![Open Source Love](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.md)                                                    



<p align="center">
    <img src="Images/git-logo.png" alt="Logo" height="60">
<h4 align="center">Git-Cheatsheet</h4></p>

---

Created by: <img src="Images/gdg-logo-trans.png" alt="GDG-LOGO" width="35px"> GDG Siliguri Open-Source Community

<p><br /></p>
## What is Git?​ :thinking::syringe:



Git is a version-control tool by which you can work in any project with teams and it will store the history and checkpoints of all the changes you are making in that project. So if you are facing any issue in current version of your project, using Git you can restore to previous stable version. Git is an essential tool for open-source contribution and any development area. :pill:



#### How to Install Git? :inbox_tray::gem:

* **Git for Windows and Mac:**

  -Go to [Git-SCM](https://git-scm.com/) :beginner:

  -Go to Downloads

  -Download for windows or mac whichever os you are using

  -Install that downloaded file

  

* **Git for Debian:**

  -Go to terminal

  -Use this command

  ```
  sudo apt-get install git
  ```

  















___



[GitHub Desktop](https://windows.github.com "GitHub Windows"):rocket:

___

**GitHub for Mac** ::rocket:

[GitHub Desktop](https://mac.github.com "GitHub Mac")

___

```
Git distributions for Linux and POSIX systems are available on the official Git SCM web site
```

___

**Git for All Platforms:**:gem:

[Git](https://git-scm.com "Git")

___



**What is a repository** :anchor::checkered_flag:

A **repository**:ledger: is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. We recommend including a *README*, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.:beginner:

* To create a repository:

                1.  In the upper right corner, next to your avatar or identicon, click  and then select **New repository**:ledger:.
                   2.     Name your repository (any name of your choice)
                   3.   Write a short description.:pencil:
                   4.   Select **Initialize this repository with a README**.:hotsprings:

___

**What is a branch in Github:**:rocket:

**Branching** ::paperclips:is the way to work on different versions of a repository at one time.
By default your repository has one branch named master which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.:moyai:

When you create a branch off the master branch, you’re making a copy, or snapshot, of master as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates.:hotsprings:



___

**To create a new branch:** :keyboard: ​

1. Go to your new repository (any name you want).

2. Click the drop down at the top of the file list that says **branch: master**.:round_pushpin:

3. Type a branch name, readme-edits, into the new branch text box.

4. Select the blue **Create branch** box or hit “Enter” on your keyboard.:milky_way:



___



**What is commit:**:checkered_flag:

On GitHub, saved changes are called commits. Each commit has an associated *commit message*, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.:partly_sunny:

___

**How to commit changes:**:round_pushpin:

   1. Click the README.md file.

   2.  Click the  pencil icon in the upper right corner of the file view to edit.

   3.  In the editor, write a bit about yourself.

   4.  Write a commit message that describes your changes.

   5.   Click **Commit changes** button:computer:

​      

___



**What are pull request:** :pushpin::arrows_clockwise:

Pull Requests are the heart of collaboration on GitHub. When you open a *pull request*, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show  *diffs*, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

___

**How to merge pull request:**:hotsprings::innocent:

In this final step, it’s time to bring your changes together – merging your readme-edits branch into the master branch.

1.       Click the green **Merge pull request** button to merge the changes into master.:speech_balloon:
2.       Click **Confirm merge**.
3.       Go ahead and delete the branch, since its changes have been incorporated, with the **Delete branch** button in the purple box.:artificial_satellite:

___



**SOME GO TO COMMANDS IN GITHUB AND THEIR USES:**:mega::bell:

MAKE CHANGES

   * $ git status

     > Lists all new or    modified files to be commited.:star2:

* $ git add [file]

  > Snapshots the file in preparation for versioning $ git reset [file] Unstages the file, but preserve its contents:boom:



*  $ git diff

  > Shows file differences not yet staged:zap:



* $ git diff --staged:hourglass:

  > Shows file differences between staging and the last file version



* $ git commit -m "[descriptive message]":speech_balloon:

  > Records file snapshots permanently in version history

___



**CONFIGURE TOOLING**:pill:

Configure user information for all local repositories

   * $ git config --global user.name "[name]":name_badge:

     > Sets the name you want atached to your commit transactions



   * $ git config --global user.email "[email address]":scissors:

     > Sets the email you want atached to your commit transactions



* $ git config --global color.ui auto:space_invader:

  > Enables helpful colorization of command line output

___



**CREATE REPOSITORIES:dart:**

 Start a new repository or obtain one from an existing URL



   * $ git init [project-name]:sunrise_over_mountains:

     > Creates a new local repository with the specified name



   * $ git clone [url]

     > Downloads a project and its entire version history

___



**GROUP CHANGES**:rainbow::rocket:

Name a series of commits and combine completed efforts



   * $ git branch

     > Lists all local branches in the current repository



   * $ git branch [branch-name]:izakaya_lantern:

     > Creates a new branch



   * $ git checkout [branch-name]:circus_tent:

     > Switches to the specified branch and updates the working directory



   * $ git merge [branch]

     > Combines the specified branch’s history into the current branch



   * $ git branch -d [branch-name]:trident:

     > Deletes the specified branch

___

**REFACTOR FILENAMES**:link:

Relocate and remove versioned files

   * $ git rm [file]

     > Deletes the file from the working directory and stages the deletion:hammer_and_wrench:



   * $ git rm --cached [file]

     > Removes the file from version control but preserves the file locally



   * $ git mv [file-original] [file-renamed]:chains:

     > Changes the file name and prepares it for commit



___

**REVIEW HISTORY**:artificial_satellite:

 Browse and inspect the evolution of project files

   * $ git log

     > Lists version history for the current branch

* $ git log --follow [file]:mandarin:

  > Lists version history for a file, including renames

   * $ git diff [first-branch]...[second-branch]

     > Shows content differences between two branches

* $ git show [commit]:mountain:

  > Outputs metadata and content changes of the specified commit

___

**REDO COMMITS**:stopwatch:
Erase mistakes and craft replacement history

   * $ git reset [commit]:chains:

     > Undoes all commits afer [commit], preserving changes locally

   * $ git reset --hard [commit]:spider_web:

     > Discards all history and changes back to the specified commit

___

**SYNCHRONIZE CHANGES**:artificial_satellite:

Register a repository bookmark and exchange version history

   * $ git fetch [bookmark]:thermometer:

     > Downloads all history from the repository bookmark

   * $ git merge [bookmark]/[branch]

     > Combines bookmark’s branch into current local branch

   * $ git push [alias] [branch]:hammer_and_wrench:

     > Uploads all local branch commits to GitHub

   * $ git pull

     > Downloads bookmark history and incorporates changes



___

**SAVE FRAGMENTS**:unicorn::rainbow:

 Shelve and restore incomplete changes

   * $ git stash

     > Temporarily stores all modified tracked files

   * $ git stash list :triangular_flag_on_post:

     > Lists all stashed changesets

   * $ git stash pop

     > Restores the most recently stashed files:world_map:

   * $ git stash drop

     > Discards the most recently stashed changeset :statue_of_liberty:
