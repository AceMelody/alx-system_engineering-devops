0x01-shell_permissions readme
0-iam_betty switches the current user to betty
1-who_am_i prints the effective username of the current user
2-groups prints all the groups the current user is part of
3-new_owner changes the owner of hello to betty
4-empty creates an empty file, hello
5-execute adds execute permissions to the owner of hello
6-multiple_permissions modifies read an execute permissions of hello
7-everybody gives all execute permissions
8-James_Bond gives the other users all permissions and none to the owner and group
9-John_Doe gives all execute permission, the owner and other users write permissions and read permissions to the owner only
10-mirror_permissions set hello to the same mode as olleh
11-directories adds execute permission to all subdirectories in the current directory
12-directory permissions creates a dorectory with the permissions 751
13-change_group changes the group owmer of hello
100-change_owner_and_group changes the owner and group of all files and directories in the current directory
101-symbolic_link_permissions changesthe owne and the grou  owner ofthe symbolic link _hello
102-if_only changes tho owner of hello to betty only if it is owned by guillaume
