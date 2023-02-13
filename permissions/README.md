0. su-Script that switches current user to the user Betty
1. whoami-Script that prints the effective username of current user
2. id -Gn-Script that prints all the groups the current user is part of
3. chown betty hello-Script that changes the owner of the file hello to the user betty
4. touch hello-Creates an empty file called hello
5. chmod u+x hello-Script that adds execute permission to the owner of the file hello
6. chmod u+x,g+x,o+r hello-Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello 
7. chmod ugo+x hello-Script that adds execution permission to the owner, the group owner and the other users, to the file hello
8. chmod 007 hello-Script that sets the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissions
9. chmod 753 hello-Script that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10.
