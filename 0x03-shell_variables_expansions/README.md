Shell, init files, variables and expansions
0-alias ---- Script uses the alias command to set "ls" equal to inputing "rm *"
1-hello_you ---- Script uses echo command to display current user. The current user is specified by the variable $USER
2-path Uses the export command to to add the directory /action to the PATH variable
3-paths ---- Script uses echo to print $PATH, then pipes into tr to seperate the fields into new lines, and then wordcount to count the lines
4-global_variables ---- Script uses printenv command to print environment variables
5-local_variables ---- Script uses set to print local variables
6-create_local_variable ---- Script sets BEST equal to School without the export command so it stays local
7-create_global_variable ---- Same as last task but adds the export command to make it global
8-true_knowledge ---- Script uses a set variable TRUEKNOWLEDGE (which equals 1209) to add it to 128 and get a sum of 1337, which is printed with echo
9-divide_and_rule ---- Script prints result of POWER devided by DEVIDE using echo and $((P/D)) format
10-love_exponent_breath ---- Script uses echo and $((B**L)) equation to print the result of BREATH to the power of LOVE
11-binary_to_decimal ---- Script uses echo expansion to display the variable BINARY(which is 10100111001) as a decimal number(base10)
12-combinations ---- Script echo's all combos of 2 letters, uses tr to put each 2 letter combo on a \n, and lastly grep's inverse to display everything but "oo" combination
13-print_float ---- Script uses printf to reformat a given variable to 2 decimal plases only
