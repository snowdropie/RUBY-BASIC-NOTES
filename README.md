# RUBY-BASIC-NOTES

COMMAND LINE

The command line is a text interface for your computer. It’s a program that takes in commands, which it passes on to the computer’s operating system to run.

$ ls                                                                                                                     

2014  2015  hardware.txt

$ a shell prompt

ls=lists 

When using the command line, we refer to folders as directories. Files and directories on your computer are organized into a filesystem.

A filesystem organizes a computer’s files and directories into a tree structure:

The first directory in the filesystem is the root directory. It is the parent of all other directories and files in the filesystem.

Each parent directory can contain more child directories and files. Here blog/ is the parent of 2014/, 2015/, and hardware.txt.

Each directory can contain more files and child directories. The parent-child relationship continues as long as directories and files are nested.

You’re probably already familiar with this tree structure - Mac Finder and Windows Explorer represent the filesystem as trees as well.

$ pwd

/home/ccuser/workspace/blog

pwd stands for “print working directory”. It outputs the name of the directory you are currently in, called the working directory.

$ cd 2015

cd stands for “change directory”. Just as you would click on a folder in Windows Explorer or Finder, cd switches you into the directory you specify. In other words, cd changes the working directory.

The directory we change into is 2015. When a file, directory or program is passed into a command, it is called an argument. Here the 2015 directory is an argument for the cd command.

$ cd .. 

To move up one directory, use cd … Here, cd .. navigates up from jan/memory/ to jan/.

$ mkdir media

The mkdir command stands for “make directory”. It takes in a directory name as an argument, and then creates a new directory in the current working directory.

Here we used mkdir to create a new directory named media/ inside the feb/ directory.

touch keyboard.txt

The touch command creates a new file inside the working directory. It takes in a filename as an argument, and then creates an empty file in the current working directory.

Here we used touch to create a new file named keyboard.txt inside the 2014/dec/ directory.

The commands we’ve covered so far are commonly used to navigate the filesystem. There are more commands you can use to master the command line, and we’ll cover them in the next lessons.

Congratulations! You’ve learned five commands commonly used to navigate the filesystem from the command line. What can we generalize so far?

The command line is a text interface for the computer’s operating system. To access the command line, we use the terminal.

A filesystem organizes a computer’s files and directories into a tree structure. It starts with the root directory. Each parent directory can contain more child directories and files.

From the command line, you can navigate through files and folders on your computer:

pwd outputs the name of the current working directory.

ls lists all files and directories in the working directory.

cd switches you into the directory you specify.

mkdir creates a new directory in the working directory.

touch creates a new file inside the working directory.
