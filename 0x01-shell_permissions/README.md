#0x01-shell_permissions Project 

This folder contains scripts which were created for the project. 

##0-iam_betty
Switches from current user to user named betty.

##1-who_am_i
Prints effective username of current user.

##2-groups
Prints groups that current user is part of.

##3-new_owner
Changes the owner of the file hello to the user betty.

##4-empty
Creates empty file called hello.

##5-execute
Adds execute permission to the owner of the file hello.

##6-multiple_permissions
Adds execute permission to the owner andgroup owner; as well as read permission to other users for to the file hello.

##7-everybody
Adds execution permission to the owner, group owner and other users for the file hello.

##8-James_Bond
Sets no permisions for the owner and group, but all permissions for all other users for the file hello.

##9-John_Doe
Sets permissions for the hello file to -rwxr-x-wx. 

##10-mirror_permissions
Mirrors permissions from the olleh file to the file named hello.

##11-directories_permissions
Recursively adds execute permission for author, group and other users in subdirectories only.

##12-directory_permissions
Creates a my_dir directory with 751 permissions in the working directory.

##13-change_group
Changes hello file group to school.

##100-change_owner_and_group
Recursively changes owner and group for files & directories to vincent and group respectively. 

##101-symbolic_link_permissions
Changes the owner to vincent and group to staff for _hello.

##102-if_only
Changes owner from guillaume to betty for hello file. 
