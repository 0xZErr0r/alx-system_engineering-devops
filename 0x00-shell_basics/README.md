#!/bin/bash - shebang symbol to excute whats in bin/bash directory

pwd = the command for getting the current directory

ls = displays the contents list of current dir

cd = a script that changes the working directory to the user’s home directory

ls -l = Display current directory contents in a long format

ls -l -a = Display current directory contents, including hidden files (starting with .). Use the long format

ls -lna = Display current directory contents: Long format, with user and group IDs displayed numerically & And hidden files (starting with .)

mkdir = a script that creates a directory named my_first_directory in the /tmp/ directory
 
mv -f = Move the file betty from /tmp/ to /tmp/my_first_directory
 
rm = Delete the file betty; The file betty is in /tmp/my_first_directory
 
rm -rf = Delete the directory my_first_directory that is in the /tmp directory
 
cd - = Write a script that changes the working directory to the previous one
 
ls -la . .. = a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
 
file = a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script
 
ln --symbolic = Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory
 
cp -u *.html .. = a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
 
mv [[:upper:]]* = a script that moves all files beginning with an uppercase letter to the directory /tmp/u
 
rm *~ = a script that deletes all files in the current working directory that end with the character ~
 
mkdir -p = a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
 
ls -la -m -v -p = a command that lists all the files and directories of the current directory, separated by commas (,)
 
??? = a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0
