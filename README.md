# 202232854_DANA_lecture_note_4
## Open Sourse Lecture Week 4 HomeWork



Introduction: This document is a lecture note about Shell command  
Please skip this file if this is not about your concern

---

**1. Shell command: pwd**  
Function: Showing the current path in a hierachical directory

**2. Shell command: cd and ls**  
ch: This command literally change the directory to directory that you gonna put after the ch
ls: **l in 'ls' command is not capital i!** 'ls' stand for list, and it lists files and directories of assigned directory.

**3. Shell command: arguments**  
This function links to cd function.  
Following arguments should be put right next to cd command
- . = current directory
- .. = upper-level directory
- /\[directory name] = absolute path
- ./\[directory name] = relative path
- ../\[directory name] = relative path

```sh
Usage example
- cd ..
- cd oss/transformers
- cd ../neuralintlab
```


**4. Shell command: options**  
This function links to ls function.  
Following options should be put right next to cd command
- l = showing detailed information in long format
- lh = same function as l, but size in units (using this funtion, b/c sometimes data size becomes enormous)
- la = list all files in the parent of the working directory in long format
- \/bin = list the files in the \/bin directory
- -l\/etc \/bin = list files in the efc and bin directory in long format

```sh
Usage example
- ls -l
- ls -lh
```
**Extra Tips!!**  
1. Press tab key: you do not have to type out all of directory spelling
2. Press "up arrow" key: you can call the past command
3. Command clear: you can wipe out all the command (we use this usually for readabillity)
   > Be careful using this command, b/c you could delete necessary contents.

---

#####Caution!
> Manipulation functions can delete or overwrite your files and directories.  
> Please backup your contents before you use this command.

---

**1. Manipulation: cp**  
Fuction: 'cp' stands for copy, and it copy files and directories  
Specific functions are below.

![cp extra function](https://github.com/kda5337/202232854_DANA_lecture_note_4/assets/144139251/36b24d5d-3fbe-455a-a0c1-205b0c8c9bfc)
  

**2. Manipulation: mv**  
Fuction: 'mv' stands for move, and it move files and directories or rename them  
Specific functions are below.

![mv extra function](https://github.com/kda5337/202232854_DANA_lecture_note_4/assets/144139251/a5dd4b12-bf5f-4fd9-b2f6-3c4717d5d13c)
  
**3. Manipulation: rm**  
Fuction: 'rm' stands for remove, and it delete files and directories ***permantely and irreversevely!***  
**YOU REALLY HAVE TO CAREFUL WITH USING THIS COMMAND**  
Specific functions are below.  

![rm extra function](https://github.com/kda5337/202232854_DANA_lecture_note_4/assets/144139251/1768ab92-08c9-4d56-a960-5042d55b809c)  

  
**4. Manipulation: mkdir**  
Fuction: 'mkdir' stands for 'make directory', and this command makes a new directory


**5. Manipulation: Wildcards**  
Pictures below explain the other functions that is not mentioned above.
Take a look if you want extra information 

![wildcard1 extra function](https://github.com/kda5337/202232854_DANA_lecture_note_4/assets/144139251/df1d6e52-3576-41ba-ac85-2f195fa30966)  
![wildcard2 extra function](https://github.com/kda5337/202232854_DANA_lecture_note_4/assets/144139251/e91d643d-b1bb-41c0-b62d-f9eb2f88fea7)  

---


***If you enter 'exit', you can exiting terminal***

##**THANK YOU FOR READING THIS DOCUMENT**
