# Git

Git is a distributed versional control system used to allow developers work collaboratively on the same files or code. It does this by storing files in a remote repository which can be accessed and *cloned* locally. Changes are monitored and *committed* to the repository locally before *pushed* to the remote repository. This allows for multiple users to to work on the same files and quickly synchronize changes. Git also improves the quality of version control by eliminating the need to self-manage versions on files and folders.

## Version Control

Version control is a system to manage versions of files and folders. Version control tracks when and what changes were made. Additionally, it allows you to view prior versions and revert to them.

## Cloning

*Cloning* in Git is used to create a copy of a remote repository, such as GitHub, to your local computer. When using Git the command to clone a repository is `git clone "repository-location"`.

## ACP

ACP is short for *add*, *commit*, *push*. This is the process to confirm and *commit* your changes from a *cloned* repository on your system to a remote repository.

### Add

After you have completed making your changes and saved your work the first step is to *add* the changes. This tells Git to track the files and stage them for *commit*. The command to do this is `git add`. This command is followed by an argument to specify which files to *add*. `git add file.md file2.html` will *add* both files, `git add *` will *add* all files in the repository, and `git add .` will *add* all files which have changes.

### Commit

After you have staged the files using *add* command, it is time to *commit* the changes. The command to do this is `git commit -m "commit message"`. The commit message should give a brief summary of why you are *committing* the changes.

### Push

Lastly, once you have *added* and *committed* the changes, you need to *push* to origin. The origin is the remote repository you cloned from. To do this you use the command `git push origin main`. In this example "main" is the name of the branch being *pushed* to but would be changed if you were using a different branch.
