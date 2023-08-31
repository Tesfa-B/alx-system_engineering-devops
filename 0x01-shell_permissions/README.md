shell script for permissions

*su: betty changes user to betty
 whoami: prints the current user
 groups: print all groups the user part of
 sudo chown betty hello : changes the ownership of the hello file to betty
 touch hello: creates an empty file named hello
 chmod 764 hello: gives the permission to add excute to  owner
 chmod 774 hello: gives the permission to add  group owner
 chmod a+x hello: gives execution permission to all
 chmod 007 hello: gives all permission to other users
 chmod 753 hello: gives permission rwx rx wx to hello 
 chmod --refrence=hello olleh: sets the mode dame as the other file
 chmod -R ugo+X . : adds execute  permission to all subdirectories of Pwd
 chmod -m 751 my_dir : creates my-dir with rwx rx r permission

