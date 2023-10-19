## Lecture note (week 4) - Open Source Software


Linux
Kernel : Core of OS that controls and communicates with hardware resource
Shell : Interface that allows users to communicate with kernel

---
#### CLI (Command Line Interface) vs GUI(Graphical User Interface)

CLI : relatively fast, basic environment for developers
GUI : relatively slow, for repetitive tasks, for daily users
---
##### [Git bash](https://git-scm.com/)     <-    Cleak and download
---

## Shell command
- pwd : shows the current path in a hierarchical directory
- cd : change directory
- ls : list files and directories
( ls command is used to list the contents of directory. It is probably the most commonly used Linux command. It can be used in a number of different ways.) Ex) ls, ls /bin, ls -1, ls -1 / etc /bin
- clear
- help command (man)
- exiting terminal (exit)
```sh
*Tip 
"tab" key  (Autocompletion)
"up arrow" key (Past commands)
```
---

## Manipulation 
(These commands may delete or overwrite your files and directories. Make Sure to backup your importent contents.)

- cp : copy files and directories (Ex) cp file1 file2, cp file1 dir1, cp -R dir1 dir2, cp -i file1 file2)
- mv : move files and directories or rename them
- rm : delete files and directories permantely and irreversevely !
- mkdir : make a new directory

---
Wildcards - pattern (example)
```sh
* 
g*
b*.txt
Data???
```
Wildcards - command (example)
```sh
cp *.txt text_files
mv dirl ../*.bak dir2
rm *~     ( Be careful !!! )
```








