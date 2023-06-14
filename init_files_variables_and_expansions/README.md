# Init files variables and expansions
## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
- What happens when you type $ ls -l *.txt
- Shell Initialization Files
- What are the /etc/profile file and the /etc/profile.d directory
- What is the ~/.bashrc file
- Variables
- What is the difference between a local and a global variable
- What is a reserved variable
- How to create, update and delete shell variables
- What are the roles of the following reserved variables: HOME, PATH, PS1
- What are special parameters
- What is the special parameter $??
- Expansions
- What is expansion and how to use them
- What is the difference between single and double quotes and how to use them properly
- How to do command substitution with $() and backticks
- Shell Arithmetic
- How to perform arithmetic operations with the shell
- The alias Command
- How to create an alias
- How to list aliases
- How to temporarily disable an alias
- Other help pages
- How to execute commands from a file in the current shell
## Requirements
### General
- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly #!/bin/bash
- A README.md file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use &&, || or ;
- You are not allowed to use bc, sed or awk
- All your files must be executable
## More Info
- Read your /etc/profile, /etc/inputrc and ~/.bashrc files.

- Look at some files in the /etc/profile.d directory.

- Note: You do not have to learn about awk, tar, bzip2, date, scp, ulimit, umask, or shell scripting, yet.
### Task 0 - <o>
0-alias > Script that creates an alias.

- Name: ls
- Value: rm *
### Task 01 - Hello you
1-hello_you > Script that prints hello user, where user is the current Linux user.
### Task 02 - The path to success is to take massive, determined action
2-path > Script that adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
### Task 03 - If the path be beautiful, let us not ask where it leads
3-paths > Script that counts the number of directories in the PATH.
### Task 04 - Global variables
4-global_variables > Script that lists environment variables.
### Task 05 - Local variables
5-local_variables > Script that lists all local variables and environment variables, and functions
### Task 06 - Local variable
6-create_local_variable > Script that creates a new local variable.

- Name: BEST
- Value: School
### Task 07 - Global variable
7-create_global_variable > Script that creates a new global variable.

- Name: BEST
- Value: School
### Task 08 - Every addition to true knowledge is an addition to human power
8-true_knowledge > Script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
### Task 09 - Divide and rule
9-divide_and_rule > Script that prints the result of POWER divided by DIVIDE, followed by a new line.

- POWER and DIVIDE are environment variables
### Task 10 - Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
10-love_exponent_breath > Script that displays the result of BREATH to the power LOVE

- BREATH and LOVE are environment variables
- The script should display the result, followed by a new line
### Task 11 - There are 10 types of people in the world -- Those who understand binary, and those who don't
11-binary_to_decimal > script that converts a number from base 2 to base 10.

- The number in base 2 is stored in the environment variable BINARY
- The script should display the number in base 10, followed by a new line
### Task 12 - Combination
12-combinations > Script that prints all possible combinations of two letters, except oo.

- Letters are lower cases, from a to z
- One combination per line
- The output should be alpha ordered, starting with aa
- Do not print oo
- Your script file should contain maximum 64 characters
### Task 13 - Floats
13-print_float > Script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.
### Task 14 - Decimal to Hexadecimal
14-decimal_to_hexadecimal > Script that converts a number from base 10 to base 16.

- The number in base 10 is stored in the environment variable DECIMAL
- The script should display the number in base 16, followed by a new line
