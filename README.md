# Text Editor - UwU Editor
Implementation of http://antirez.com/news/108

## To Run:
execute the make command to compile UwUeditor.c file,

  $ make
  
execute the created a.UwUeditor directly to open empty editor with,

  $ ./a.UwUeditor
  
execute with name of file as argument to open a preexisting file,

  $ ./a.UwUeditor filename


## Commands within editor
Ctrl-Q : quit -> if not aldready saved will prompt to emter Ctrl-Q 3 times to confirm discarding changes \n

Ctrl-S : save -> will prompt to ask for filename to save as if new file, or will save over existing file \n

Ctrl-F : search/find
