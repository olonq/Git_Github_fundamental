# Git Cheat Sheet

This cheat sheet contains a list of commonly used Git commands:

## Setup

`git config --global user.name "[name]"`: Sets the name you want attached to your commit transactions.

`git config --global user.email "[email address]"`: Sets the email you want attached to your commit transactions.

`git config --global color.ui auto`: Enables helpful colorization of command line output.

## Create

`git init [repository name]`: Starts a new repository.

`git clone [url]`: Downloads a project and its entire version history.

## Local Changes

`git status`: Shows the status of changes as untracked, modified, or staged.

`git diff`: Shows file differences not yet staged.

`git add [file]`: Stages the file for commit to your local repository.

`git commit -m "[descriptive message]"`: Commits file permanently to version history.

## Commit History

`git log`: Shows a commit history for the active branch.

`git log --oneline`: Shows a summary of the commit history for the active branch.

## Branches & Tags

`git branch`: Lists all local branches in the current repository.

`git branch [branch-name]`: Creates a new branch.

`git checkout [branch-name]`: Switches to the specified branch and updates the working directory.

`git merge [branch-name]`: Combines the specified branch’s history into the current branch.

`git tag [tag-name]`: Marks specific points in history as important.

## Update & Publish

`git fetch [bookmark]`: Downloads all history from the repository bookmark.

`git merge [bookmark]/[branch]`: Combines bookmark’s branch into current local branch.

`git push [alias] [branch]`: Uploads all local branch commits to GitHub.

`git pull`: Updates your current local working branch with all new commits from the corresponding remote branch on GitHub.

## Redo Commits

`git reset [commit]`: Undoes all commits after `[commit]`, preserving changes locally.

`git reset --hard [commit]`: Discards all history and changes back to the specified commit.

Remember, this is just a list of some of the most commonly used Git commands. There are many more commands available in Git's command line interface.
