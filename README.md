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
Extra functions are below.

![cp extra function]





