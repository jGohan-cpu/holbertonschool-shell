# HolbertonSchool-Shell / Permissions

### Explanation Of Exercises
* Exercise 0 - the "su betty" command was used to switch the current user to betty. 
* Exercise 1 - the "id un" command was used to print the effective username of the current user.
* Exercise 2 - the "id -nG" command was used to print all the groups the current user is part of.
* Exercise 3 - the "sudo chown betty hello" command was used to change the owner of the file hello to the user betty.
* Exercise 4 - the "touch hello" command was used to create a file named "hello".
* Exercise 5 - the "chmod u+x hello" command was used to make a file executable.
* Exercise 6 - the "chmod u+x,g+x,o+r hello" command was used to add execute permission to the owner and the group owner, and read permission to other users, to the file hello.
* Exercise 7 - the "chmod ugo+x hello" command was used to add execution permission to the owner, the group owner and the other users, to the file hello.
* Exercise 8 - the "chmod 007 hello" command was used to give all permissions to the other users and no permission at all to the owner and grop.
* Exercise 9 - the "chmod 753 hello" command was used to set the mode to "rwxr-x-wr".
* Exercise 10 - the "chmod --reference=olleh hello" command was used to set the mode of the file hello the same as olleh’s mode.
* Exercise 11 - the "chmod -R a+x **/" command was used to add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
* Exercise 12 - the "mkdir -m 751 my dir" command was used to create a directory called my dir with permissions 751 in the working directory.
* Exercise 13 - the "chgrp school hello" command was used to  change the group owner to school for the file hello.
* Exercise 14 - the "chown vincent:staff **" command was used to change the owner to vincent and the group owner to staff for all the files and directories in the working directory.
* Exercise 15 - the "chown -h vincent:staff hello" command was used to change the owner and the group owner of  hello to vincent and staff respectively.
* Exercise 16 - the "chown --from=guillaume vincent hello" command was used to change the owner of the file hello to vincent only if it is owned by the user guillaume.
