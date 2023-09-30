## CLI(Command Line Interface)
#### standard output
```
ex ) screen
$ ">" : save output in a file.
$ ">>" : appends output to an exitsing file ( if already exists ) else create to a new file.
```
#### standard input
```
ex ) keyboard
$ "<" : redirect input from a file
```
---
#### pipeline |
```
Pipeline feeds output of previous command to input of next command.
q : exit the screen.
```
#### permissions
; files and directories have a permission assigned differently to owner/ group / others.
"chmod" : how to change permissions
Change the permission of a file “word.txt” that only the owner(you) can read and write,  but all the others(including others in the group) can only read it. No execution is needed  for all users.
#### superuser
Some commands need superuser’s privilleges.
"sudo” before the command if you are a superuser
“exit” to get out of a superuser session
