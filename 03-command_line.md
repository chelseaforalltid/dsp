# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

###Q1.  Cheat Sheet of Commands  

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do, focused on things that are new, interesting, or otherwise worth remembering.

`ls -a` = list all files and folders  
`pwd` = print working directory  
`cd /` = go to root  
`man` <command> = shows manual   
`cat` <fileName> = show content of file (less, more)  
`mkdir` = create new folder  
`cp` image.jpg newimage.jpg = copy and rename a file  
`rm` <fileName> .. = delete file (s)  
`rm -r` <foldername>/ = delete folder  
`touch` <fileName> = create or update a file  
`find -name` <fileName> = find file  
`grep -r` <text> <foldername>/ = search for file names with occurence of text     
---

###Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

`ls` lists files in your current directory      
`ls -a` lists all files in your current directory (includes hidden files preceded by a dot (.))      
`ls -l` lists in long format    
`ls -lh` lists in long format with unit suffixes to reduce numbers shown for file size    
`ls -lah` lists all files in long format (including hidden) with unit suffixes    
`ls -t` lists files sorted by time (most recently modified first  
`ls -Glp` lists files in long format with color formatting and with slashes for folders

---

###Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

`ls -F` flags filenames       
`ls -1` displays entries one per line      
`ls -r` displays in reverse order       
`ls -R` displays subdirectories       
`ls -o` displays in a comma separated list     

---

###Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

`xargs` takes strings from the standard input and executes a utility with those strings as an argument.    
It can be used with `find` and `grep` to search for some files, and then look for a certain word in those files.    

`find . -name "*.java" | xargs grep "Stock"`




 

