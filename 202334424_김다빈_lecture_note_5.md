## Lecture note (week 5) - Open Source Software

---
#### I/O Redirection : Standard Output
Standard Output  = screen

Use '>' after command to create and save the
output in a file.
<command>
cat : display the content of a text file.

Use '>>' appends output to an existing file, or create and write to a new file if it doesn't exist.

---

#### I/0 Redirection : Standard Input
Standard Input = is from keyboard

Use '<' to redirect input from a file.
You can mix '<' and '>' together in single line.

---

#### Pipelines '|'
Pipeline feeds output of previous commandto input of next command.
(command1 | command2 | command3)
command1's output will be command2's input ~~
```sh
 Press 'q' key to exit the screen.
```

---
#### Expansion
Special characters expand its meaning when given to shell commands.
```sh
Tip : blackslash '\'
Backslash can be used to ignore line change in command ('enter'), to enter a long command in multiple lines.
```
---

#### Permissions
Linux is a multi-user system.
Files and directories have a permission assigned differently to owner / group / others.
```sh
Changing permission
"chmod" changes permissions.
777
755
700
666
644
600
```
---
#### Superuser
A superuser has all system administation authority. 
Some commands need superuser's previlleges.
Put "sudo" before the command if you are superuser.
```sh
Type "exit" to get out of a superuser session.
```
---
#### Text Editors
You can choose CLI-based or GUI-based text editors.
```sh
vi, vim
Emacs
nano
gedit
kwrite
```

---


```sh
Tip
type 'history' to see previous command history, or save it to a text file.
```









