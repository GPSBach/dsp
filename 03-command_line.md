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

> > REPLACE THIS TEXT WITH YOUR RESPONSE

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

>> `ls`  - list files and folders in current directory  
>> `ls -a` - list all files and folders in current directory including hidden  
>> `ls -l` - detailed list view including user permissions, dates, and sizes  
>> `ls -lh` - as above with files sizes in human readable format  
>> `ls -lah`  - as above with hidden files  
>> `ls -t` - sorts files by date modified  
>> `ls -Glp` - list form, long format, with backslash following directories  


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

>> `ls -lahS` - list all files sorted by file size  
>> `ls -lal` - list all files and evaluate symbolic links  
>> `ls -laut` - list by last access time instead of last modification time  
>> `ls -laR` - list recursively  
>> `ls -lAT` - list detailed time info  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

>> xargs executes other bash commands.  This may seem like its not especially useful, but it can actually be quite powerful, allowing one to, for example, loop a bash command over multiple inputs in a single line.  
>> for example, if I wanted to make 3 new directories in a single command, I could use:  
>> `echo 'data analysis results' | xargs mkdir`
>> `ls`  
>> `data analysis results`


 

