# Linux beginner

choose whatever Linux distro comes to your mind and get started in that one [ubuntu,mint,fedora,....] anyone and get going


#Basic part of Linux commands

1) #Most important things
 Before getting your hands dirty, you must know what is man, pipe "|"symbol mean , and yes what is flag.


ok so lets begin :--

## man command
this commands show the detail of every command available on your pc i.e. what are the possible combination you can perform with the command , different flags available
for example:-
ls -l  will list the things present directory in long details i.e. with permisions it has and groups etc.

### pipe symbol
some time you need to do other operation on the result you received on terminal there this symbol comes in handy it allows you to perform some other action on the output just received.
lets say you ran cat command what it does it simply shows you the content of the files
but when piped with other command such as grep you can do other things like

cat a.txt | grep "he"
this will show all the lines in which he word is present
a.txt is the file we operated on. 




### flags
flags :- its used to change/manipulate the default behaviour of the command 
such as: 

ls command list the directory and files 
but when used with a flag -a it shows all the hidden files and directories

ex: ls -a

you can see and other flags available for ls and other commands in manual pages of the command [ man command]

 
