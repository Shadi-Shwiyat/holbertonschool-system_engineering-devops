Today we are adding permissions to files and directories

0. My Name is Betty
This script uses su command to change the super user to Betty
1. Who am I
This script uses the whoami command to list the current user
2. Groups
This script uses the groups command to list the current groups the user is in
3. New owner
This script uses the chown command to change the owner of the hello file to user betty
4. Empty
This script uses the touch command to write an empty file hello
5. Execute
This script uses chmod command to add permission of the user (u+x)
6. Multiple Permissions
This script uses chmod command to add x permission to the u and g and r permission
all others
7. Everbody!
This script uses chmod command with a+x to give exe permissions to all users
8. James Bond
This script uses chmod with binary transulation to get 007 permissions
9. John Doe
This script uses chmod with binary transulation to get 753 permissions
10. Look in the mirror
This script uses the chmod with --refernce option to mirror olleh and hello files
11. Directories
This script adds exe permission to all subdirectories and not files using chmod a+X and capitolization specifies directories with the X
12. More Directories
Uses the mkdir command with -m option to create a directory and set permissions to 751 at the same time
13. Change group
This script changes the group owner to school for the file hello with the chgrp command
