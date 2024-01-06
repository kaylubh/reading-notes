# Linux Command Line

## The Command Line

- Within the terminal there is the shell which defines how the terminal behaves and looks. The most common is bash. We have been using zsh.

## Basic Navigation

- `pwd` (print working directory) to find the current location and `ls` (list) to list out all the files and folders in the current directory. `cd` (change directory) is used to move between directories by providing a path as an argument, without any arguments will take you back to your home directory.
- Absolute paths which specify the location in relation to the root directory. Will always begin with a forward slash `/`. Relative paths are in relation to the current directory of the terminal and will not begin with a slash.
- Shortcuts:
  - tilde `~` : home directory
  - dot `.` : current directory
  - dot dot `..` : parent of the current directory

## More About Files

- In linux, everything is considered a file including directories (folders).
- Files in linux do not use extensions but linux reads the file itself to determine what kind of file it is. The command `file[path]` will return the type of a file if you need to check.
- Linux is case sensitive.
- Spaces are allowed in file names but can cause issues with spaces used to separate commands in the terminal. To fix this use quotes or escape characters, alternatively don't use spaces in file names.
- Hidden files are created by beginning the file name with a dot `.`. To view hidden files use `ls -a`.

## Manual Pages

- Manual pages list the full details of the commands available on a system.
- Use `man [command]` to return a manual page explaining that command and the options/arguments that can be used with it and what they do.
- To search the manual pages use `man -k [search]`. To search within a manual page use `/[search]` and `n` to move between multiple results.
- When using options with commands there are short hand `-` and long hand `--` versions. For example `ls -a` is the shorthand for `ls --all`, both do the same thing. Shorthand versions allow you to chain multiple options together easily `ls -al`.

## File Manipulation

- `mkdir` creates a new directory at the current location or at the path specified if a full path is given.
- `rmdir` removes a directory at the path specified. Directories must be empty before they are removed.
- `touch` is used to create an empty file when provided with the name.
- `cp` is used to copy a file but provided the source and destination.
- `mv` will move a file from a source to a destination. `mv` can also be used to rename a file if the paths are the same.
- `rm` is used to remove a file by providing the path. It can also be used to remove directories that aren't empty by adding the recursive `-r` option, `rm -r [directory]`.

## [Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

## References

- [Ryans Tutorials: Linux Tutorial](https://ryanstutorials.net/linuxtutorial/)
