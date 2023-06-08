## 0. My name is Betty
*su betty* Create a script that switches the current user to the user betty.
## 1. Who am I
*id -un* Write a script that prints the effective username of the current user.
## 2. Groups
*id -Gn* Write a script that prints all the groups the current user is part of.
## 3. New Owner
*chown betty hello* Write a script that changes the owner of the file hello to the user betty.
## 4. Empty!
*touch hello* Write a script that creates an empty file called hello.
## 5. Execute
*chmod u+x hello* Write a script that adds execute permission to the owner of the file hello.
## 6. Multiple permissions
*chmod ug+x,o+r hello* Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
## 7. Everybody!
*chmod ugo+x hello* Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
## 8. James Bond
*chmod 007 hello* Write a script that sets the permission to the file hello as follows:Owner: no permission at all, Group: no permission at all, Other users: all the permissions
## 9. John Doe
*chmod 753 hello* Write a script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
## 10. Look in the mirror
*chmod --reference=olleh hello* Write a script that sets the mode of the file hello the same as olleh’s mode.
## 11. Directories
*chmod -R +X .* Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
## 12. More directories
*mkdir -m 751 my_dir* Create a script that creates a directory called my_dir with permissions 751 in the working directory.
## 13. Change group
*chgrp school hello* Write a script that changes the group owner to school for the file hello
## 14. Owner and group
>chown vincent:staff *
Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
## 15. Symbolic links
*chown -h vincent:staff _hello* Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.
## 16. If only
*chown --from=guillaume betty hello* Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

