## 0x01. Shell, permissions

su = Create a script that changes your user ID to betty. You should use exactly 8 characters for your command (+1 character for the new line). You can assume that the user betty will exist when we will run your script

whoami = Write a script that prints the effective userid of the current user.

groups = Write a script that prints all the groups the current user is part of.

chown = Write a script that changes the owner of the file hello to the user betty.

touch = Write a script that creates an empty file called hello.

chmod u+x = Write a script that adds execute permission to the owner of the file hello. The file hello will be in the working directory

chmod u+x,g+x,o+r = Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. The file hello will be in the working directory.

chmod ugo+x = Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello. The file hello will be in the working directory,  You are not allowed to use commas for this script

chmod 007 = Write a script that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
The file hello will be in the working directory You are not allowed to use commas for this script

chmod 753 = Write a script that sets the mode of the file hello to this:
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
The file hello will be in the working directory
You are not allowed to use commas for this script

chmod --reference = Write a script that sets the mode of the file hello the same as olleh’s mode.
The file hello will be in the working directory
The file olleh will be in the working directory

chmod -R a+X ./ = Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

mkdir -m 751 = Create a script that creates a directory called my_dir with permissions 751 in the working directory.

chgrp = Write a script that changes the group owner to school for the file hello
The file hello will be in the working directory

chown -R vincent:staff ./ = Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

chown -h vincent:staff _hello = Write a script that changes the owner and the group owner of the file _hello to vincent and staff respectively.
The file _hello is in the working directory
The file _hello is a symbolic link

chown --from=guillaume betty hello = Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.
The file hello will be in the working directory

telnet towel.blinkenlights.nl = Write a script that will play the StarWars IV episode in the terminal.

 = Create a man that looks exactly like this one and passes all checks.
