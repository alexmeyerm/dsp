# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

- pwd # show current working directory path
- mkdir directoryName # creating a directory
- rm -R directoryName # deleting a directory
- touch fileName # creating a file using `touch` command
- rm fileName # deleting a file
- mv fileName newFileName # renaming a file
- ls -a # listing hidden files
- cp fileName otherFileName # copying a file from one directory to another
- tail -5 fileName # show the last 5 lines of a file (any N lines.  Works with head as well)
- cat fileName # show contents of a File
- chmod 755 fileName # Give permissions to a file Read-Write-Execute/Owner-Group-All

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

- ls # List files in a directory
- ls -a # List all files, including hidden, in a directory
- ls -l # Show details of each file
- ls -lh # Show details in a human readable size
- ls -lah # Show details af all files, including hidden ones
- ls -t # Sort file list by datetime
- ls -Glp # Show files, with details, with an / appended to each one.  Do not show group names

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

- ls -d # Show only directories in a directory, not files
- ls -L # Show those files with symbolic link, with their reference
- ls -m # Show list of files as a comma separated list
- ls -R # Show files, folders AND subfilders
- ls -1 # Show each file in a new line

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs takes a list of parameters (Normally, a list or arguments passed by another piped function) and executes a function to each one of them
> > Examples:
> > > echo 'one two three' | xargs mkdir  # Will create three directories called: one, two and three

> > > ls | xargs rm -fr # Will remove each file of the directory.  Faster than rm -fr *

 

