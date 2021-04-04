# The Command Line

##  what is the Command Line?

A command line, or terminal, is a text based interface to the system.

The command line typically presents you with a prompt. Here is an example:

 ## *user@bash: ls -l /home/ryan*
 
Let's break it down:

1.  A prompt ( user@bash )
2.  A command ( ls )
3.  A command line arguments ( -l /home/ryan )

- Important to note, these are separated by spaces (there must be a space between the command and the first command line argument also). 
- Most commands produce output and it will be listed straight under the issuing of the command.
- After the command has run and the terminal is ready for you to enter another command the prompt will be displayed.


## Opening a Terminal
Opening a terminal is fairly easy.

#### - Mac: Applications -> Utilities. Or  key combination 'command + space', then start typing Terminal and it will show up.
#### - Linux: Applications -> System or Applications -> Utilities. Or 'right-click' on the desktop and there may be an option 'Open in terminal'.
#### - Windows: you will need an SSH client. A rather good one is Putty (free).


## The Shell, Bash

Within a terminal you have what is known as a shell. Bash which stands for "Bourne again shell" is the most common shell available. 

To know which shell you are using use a command called "echo $SHELL". As long as it prints something to the screen that ends in bash then all is good.

## Linux Basic Commands Every User Should Know:

The first command we neeed learn is "pwd" which stands for Print Working Directory. It tells you what your current or present working directory is.

The command "ls". It's short for list. It's used to display the contents of your current working directory.
To see the content of other directories, type ls and then the directory’s path. For example, "ls /home/username/Documents" to view the content of Documents.


## Paths:

### Relative path
A file or directory location relative to where we currently are in the file system.

### Absolute path
A file or directory location in relation to the root of the file system.

## cd command
To navigate through the Linux files and directories.

## Everything is a File 
Everything to Linux is actually a file. A text file is a file, a directory is a file; what does it mean? That means that Linux is an Extensionless System.

Meaning??

file.exe - an executable file, or program.
file.txt - a plain text file.
file.png, file.gif, file.jpg - an image.

In other systems such as Windows the extension is important and the system uses it to determine what type of file it is. Under Linux the system actually ignores the extension and looks inside the file to determine what type of file it is.

## But Linux is Case Sensitive
This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this. As such it is possible to have two or more files and directories with the same name but letters of different case.

## Everything is a file under Linux
Even directories.
## Linux is an extensionless system
Files can have any extension they like or none at all.
## Linux is case sensitive
Beware of silly typos.
