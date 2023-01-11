Today we are learning some shell basics
Tasks
0. Where am i?
This script uses pwd and the filename to print the absolute path of the current working directory
1. Whats in there?
This script uses ls to list all documents of current directory
2. There is no place like home
This script uses cd to take the user to the home directory
3. The long format
This script uses ls and the option -l to list contents in long format
4. Hidden Files
This script adds the -a option to the previous scripts to make ls -la to show the hidden files and in long format
5. I love numbers
This script adds the -n option to show user and group IDs displayed numerically so it's ls -lan
6. Welcome
This script creates the directory my_first_directory in the tmp/ directory using the mkdir command
7. Bety in my first directory
This script moves file betty from /tmp/ to tmp/my_first_directory using the mv command
8. Bye bye Betty
This script uses the rm command to delete the file betty
9. Bye bye My first directory
This script build on the last one by adding the -rf option to delete a not empty directory
10. Back to the future
This script uses cd with a - to go back to the previous directory you were at regardless of direction
11. Lists
This script uses the ls commaned with -la option and in order list files in . .. and /boot
12. File type
This script uses the file command to list the type of file "iamafile" is in the /tmp directory
13. We are symbols, and inhabit symbols
This script uses the ln command with the -s option for a symbolic link between /bin/ls and __ls__
14. Copy HTML files
This script uses the cp command with the -un options to copy all .html files to the parent of the working directory without overwriting any newer files
