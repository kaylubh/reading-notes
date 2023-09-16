# The Terminal (The Command Line)

These notes explain how to use some basic commands in a terminal or command line and the importance of a text/code editor for development.

## Text/Code Editor Key Features

When selecting a text or code editor there are some important features which will help determine its usefulness.

1. **Code Completion:** This will allow you to complete code faster and more accurately
2. **Syntax Highlighting:** This will distinguish between different elements in the code and identify patterns
3. **Themes:** This allows you to choose color themes that work well fpr your own work style and reduce strain on your eyes
4. **Extensions:** This allows you to extend the base functionality of the editor in order to support more languages or add other useful features to make development easier or more efficient

## Commands

Commands are used to instruct the terminal and obtain information from the terminal. The following basic commands allow you to navigate and create directories (folders) and files.

### `pwd`

The command `pwd` is short for print working directory. When you enter this command, the terminal will display which directory you are currently in.

### `ls`

The command `ls` is short for list. When you enter this command, the terminal will display all directories and files inside your current directory.

### `cd`

The command `cd` is short for change directory. When you enter this command, the terminal will move directories to argument specified after `cd`. For example, `cd new-folder` will move the command line to a directory named "new-folder". Entering `cd` without an argument will return you to your home directory.

### `mkdir`

The command `mkdir` is short for make directory. When you enter this command, the terminal will create a directory with name specified after the command. For example, `mkdir new-folder` will create a new directory titled "new-folder".

### `touch`

The command `touch` is used to create a new file. When you enter this command, the terminal will create a new file with the name and file type specified after the command. For example, `touch new-file.md` will create a new markdown file titled "new-file.md" in the current directory.

## Arguments

Arguments are additional instructions added to commands which are required for some commands or optionally modify how a command executes. Arguments can also be used reduce the number of commands required to execute a desired action.

### `cd` Arguments

In order for the `cd` command to navigate you to a directory other than your home directory, you will need to add an argument after the command. `cd projects` will move the current directory to the projects directory as long as it exists within that directory. `cd ..` uses a relative path to move from the current directory to its parent directory.

### `ls` Arguments

An argument can be added to `ls` to show the contents of a directory other than the current directory. `ls projects/new-project` will list the contents of the "new-project" directory which is part of the "projects" directory. This will not move the command line from the current directory.

### `mkdir` and `touch` Arguments

The `mkdir` and `touch` commands require an argument in order to execute successfully. You will new to specify the name, and in the case of a file you will also need to specify the file type. `mkdir new-project` will create a new directory with the name "new-project". `touch new-project/newfile.md` will create a markdown file, specified by the file extension ".md". This argument will also name the file "newfile" and create the file inside the "new-project" directory.
