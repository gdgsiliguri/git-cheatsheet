What is Github?
GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.
How to Install:
GitHub provides desktop clients that include a graphical user interface for the most common repository actions and an automatically updating command line edition of Git for advanced scenarios.
GitHub for Windows
 https://windows.github.com
GitHub for Mac :
https://mac.github.com
Git distributions for Linux and POSIX systems are available on the official Git SCM web site.
Git for All Platforms:
 https://git-scm.com
What is a repository:
A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. We recommend including a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository. It also offers other common options such as a license file.
To create a repository:
1.       In the upper right corner, next to your avatar or identicon, click  and then select New repository.
2.       Name your repository (any name of your choice).
3.       Write a short description.
4.       Select Initialize this repository with a README.
 
What is a branch in Github:
Branching is the way to work on different versions of a repository at one time.
By default your repository has one branch named master which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.
When you create a branch off the master branch, you’re making a copy, or snapshot, of master as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates.
 
To create a new branch:
1.       Go to your new repository (any name you want).
2.       Click the drop down at the top of the file list that says branch: master.
3.       Type a branch name, readme-edits, into the new branch text box.
4.       Select the blue Create branch box or hit “Enter” on your keyboard.
What is commit:
On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.
How to commit changes:
1.       Click the README.md file.
2.       Click the  pencil icon in the upper right corner of the file view to edit.
3.       In the editor, write a bit about yourself.
4.       Write a commit message that describes your changes.
5.       Click Commit changes button
 
What are pull request:
Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.
How to merge pull request:
In this final step, it’s time to bring your changes together – merging your readme-edits branch into the master branch.
1.       Click the green Merge pull request button to merge the changes into master.
2.       Click Confirm merge.
3.       Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.
 
SOME GO TO COMMANDS IN GITHUB AND THEIR USES:
 
MAKE CHANGES
$ git status
 Lists all new or modified files to be commited.
$ git add [file]
Snapshots the file in preparation for versioning $ git reset [file] Unstages the file, but preserve its contents
 $ git diff
 Shows file differences not yet staged
 $ git diff --staged
Shows file differences between staging and the last file version
 $ git commit -m "[descriptive message]"
Records file snapshots permanently in version history
CONFIGURE TOOLING
Configure user information for all local repositories
 $ git config --global user.name "[name]"
Sets the name you want atached to your commit transactions
$ git config --global user.email "[email address]"
Sets the email you want atached to your commit transactions
$ git config --global color.ui auto
Enables helpful colorization of command line output
CREATE REPOSITORIES
 Start a new repository or obtain one from an existing URL
 $ git init [project-name]
 Creates a new local repository with the specified name
 $ git clone [url]
Downloads a project and its entire version history
 
GROUP CHANGES
Name a series of commits and combine completed efforts
 $ git branch
 Lists all local branches in the current repository
 $ git branch [branch-name]
 Creates a new branch
 $ git checkout [branch-name]
 Switches to the specified branch and updates the working directory
 $ git merge [branch]
Combines the specified branch’s history into the current branch
 $ git branch -d [branch-name]
Deletes the specified branch
REFACTOR FILENAMES
 Relocate and remove versioned files
 $ git rm [file]
 Deletes the file from the working directory and stages the deletion
$ git rm --cached [file]
 Removes the file from version control but preserves the file locally
$ git mv [file-original] [file-renamed]
 Changes the file name and prepares it for commit
 
REVIEW HISTORY
 Browse and inspect the evolution of project files
 $ git log
Lists version history for the current branch
$ git log --follow [file]
Lists version history for a file, including renames
$ git diff [first-branch]...[second-branch]
Shows content differences between two branches
 $ git show [commit]
Outputs metadata and content changes of the specified commit
REDO COMMITS
Erase mistakes and craft replacement history
 $ git reset [commit]
 Undoes all commits afer [commit], preserving changes locally
$ git reset --hard [commit]
Discards all history and changes back to the specified commit
SYNCHRONIZE CHANGES
Register a repository bookmark and exchange version history
$ git fetch [bookmark]
 Downloads all history from the repository bookmark
$ git merge [bookmark]/[branch]
Combines bookmark’s branch into current local branch
 $ git push [alias] [branch]
 Uploads all local branch commits to GitHub
$ git pull
Downloads bookmark history and incorporates changes
 
SAVE FRAGMENTS
 Shelve and restore incomplete changes
 $ git stash
Temporarily stores all modified tracked files
 $ git stash list
Lists all stashed changesets
 $ git stash pop
 Restores the most recently stashed files
$ git stash drop
Discards the most recently stashed changeset
