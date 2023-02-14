0-iam_betty: su , Create a script that switches the current user to the user betty.

Who am I,command is whoami, Write a script that prints the effective username of the current user.

Groups Write a script that prints all the groups the current user is part of. 

New owner, command sudo chown you some file, Write a script that changes the owner of the file hello to the user betty.

Execute , command touch hello, Write a script that adds execute permission to the owner of the file hello. 

Multiple permissions, command chmod 754 hello, Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. 

 Everybody!, command chmod ugo+x hello, Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello.

James Bond, command chmod 007 hello, Write a script that sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissions

11 Directories: Command chmod a+X *, Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12 More directories , command mkdir -m permissions name directory, Create a script that creates a directory called my_dir with permissions 751 in the working directory.


