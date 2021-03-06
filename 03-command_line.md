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

> > 1) show current working directory path: **wpd**
> > 2) creating a directory: **mkdir**
> > 3) deleting a directory: **rmdir**
> > 4) creating a file: **touch**
> > 5) deleting a file: **rm**
> > 6) renaming a file: **mv file1 file2**
> > 7) listing hidden files: **ls -a**
> > 8) copying a file from one directory to another: **mv file directory**
> > 9) changing directory: **cd**
> > 10) showing the manual of the inputted command: **man**

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

> > `ls`: list all files and directories  
> > `ls -a` : include hidden files  
> > `ls -l` : list long format  
> > `ls -lh`: list long format with readable file size  
> > `ls -lah`: list long format with readable file size including hidden files  
> > `ls -t` : sort by time and date  
> > `ls -Glp`: list long format, adds a / at the end of directories and in a long listing, don't print group names

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > `ls -d`: Displays only directories.  
> > `ls-m`: Displays the names as a comma-separated list.  
> > `ls-R`: Displays subdirectories as well.  
> > `ls-1`: Displays each entry on a line.  
> > `ls-q`: Displays all nonprinting characters as ?  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > It builds an execution pipeline from standard input.  
> > Example :   
> > find *.txt | xargs rm

 

