# Git Breakdown

## Working Directory

    -   Area where all of our files and directories are living all the time.
    -   Use 'git init' to initialize git in the current directory.

## Staging Area

    -   Files and directories that we explicitly add to the staging area.
    -   Use 'git add <file>' to add files, changes or directories from the working directory to the staging area.

## Git Repository

    -   Where all our snapshots are stored.
    -   Use 'git commit -m <"message">' to add the changes in the staging area to the git repository. As a convencion use a present tense verbe as the very first word of the message followed by a short description.

## Status

    -   Use 'git status' to check the current stat of the repository.

## History

    -   Use 'git log' to see all the changes committed to the repository.

## Adding all files and folders in a directory

    -   Use 'git add -A' to add all the files and folders in the current directory.

## Adding multiple files of a certain file type

    -   Use 'git add *.<file type>' to add all the files of the given file type to the staging area.

## Removing files

    -   Use 'git reset HEAD <file>' to remove a file from the staging area.

## Ignoring files

    -   Create a '.gitignore' file and list all the files and directories to be ignored.

## List all branches

    -   Use 'git branch' to see all of the branches in the current repository.

## Adding branches

    -   Use 'git checkout -b <new_branch_name>' to create a new branch.

## Changing branches

    -   Use 'git checkout <branch_name>' to switch to that branch.

## Merging branches

## Removing branches
