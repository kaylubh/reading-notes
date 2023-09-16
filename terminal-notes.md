# The Terminal (The Command Line)

These notes explain how to use some basic commands in a terminal or command line and the importance of text/code editor for development.

## Text/Code Editor

## Commands

Commands are used to instruct the terminal and obtain information from the terminal. The following basic commands allow you to navigate and create directories (folders) and files.

### pwd

The command `pwd` is short for print working directory. When you enter this command, the terminal will display which directly you are currently in.

### ls

The command `ls` is short for list. When you enter this command, the terminal will display all directories and files inside your current directory.

### cd

The command `cd` is short for change directory. When you enter this command, the terminal will move directories to argument specified after `cd`. For example, `cd new-folder` will move the command line to a directory title "new-folder".

### mkdir

The command `mkdir` is short for make directory. When you enter this command, the terminal will create a directory with name specified after the command. For example, `mkdir new-folder` will create a new directory titled "new-folder".

### touch

The command `touch` is used to create a new file. When you enter this command, the terminal will create a new file with the name and file type specified after the command. For example, `touch new-file.md` will create a new markdown file titled "new-file.md" in the current directory.

## Arguments

cd projects
mkdir new-project
touch new-project/newfile.md
cd ..
ls projects/new-project
