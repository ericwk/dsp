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

>>
* pwd = show current directory path
* mkdir<directory name> = create a directory named "directory name"
* rmdir<directory name> = delete a directory named "directory name"
* touch<file name> = create a file named "file name"
* rm<file name> = delete a file named "file name"
* mv<file name 1><file name 2> = rename a file named "file name 1" to "file name 2"
* ls -a = list file in current directory incuding hidden files (file name begins with a ".")
* cp<path 1><path 2> = copy file at "path 1" to "path 2"
* rmdir<directory name> = delete directory named "directory name"
* man<command> = view Linux manual entry for "command" 
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

>>
* ls = list directory contents
* ls -a = list directory contents including files with names that begin with "." (hidden files)
* ls -l = list directory contents using long format
* ls -lh = list directory contents using long format and unit suffixes (reduced digits) for file size
* ls -lha = list directory contents using long format, unit suffixes (reduced digits) for file size, and include hidden files
* ls -t = list directory contents sorted by time modified (most recent first)
* ls -Glp = list diretory content in long format, in colorized name format with a slash after names of contents that are directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

>>
* ls -d = list directory contents listing directories only
* ls -m = list directory contents streaming comma separated names across the output page horizontally (rather than in vertical columns) 
* ls -u = list directory contents sorted by time of last access (most recent first)
* ls -c = list directory contents sorted by time of last change (most recent first)
* ls -S = list directory contents sorted by file size (largest first)




---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

>> xargs executes commands one at a time that are taken from standard input
For example:
find <directory name><file name> | xargs rm
 finds file named "file name" in or below directory "directory name" and removes it

 

