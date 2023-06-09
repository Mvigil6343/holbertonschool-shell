# Shell, I/O redirections and filters
## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## Shell, I/O Redirection
- What do the commands head, tail, find, wc, sort, uniq, grep, tr do
- How to redirect standard output to a file
- How to get standard input from a file instead of the keyboard
- How to send the output from one program to the input of another program
- How to combine commands and filters with redirections

## Special Characters
- What are special characters
- Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them

## Other Man Pages
- How to display a line of text
- How to concatenate files and print on the standard output
- How to reverse a string
- How to remove sections from each line of files
- What is the /etc/passwd file and what is its format
- What is the /etc/shadow file and what is its format

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly #!/bin/bash
- A README.md file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use backticks, &&, || or ;
- All your files must be executable
- You are not allowed to use sed or awk

## More Info
Read your /etc/passwd and /etc/shadow files.

Note: You do not have to learn about fmt, pr, du, gzip, tar, lpr, sed and awk yet.

### Task 00 - Hello World 
0-hello_word > Script that prints "Hello, World", followed by a new line to the standard output.
### Task 01 - Confused Smiley
1-confused_smiley > Script that displays a confused smiley "(Ôo)'.
### Task 02 - Let's display a file
2-hellofile > Script that displays the content of the /etc/passwd file.
### Task 03 - What about 2?
3-twofiles > Sctipt that displays the content of /etc/passwd and /etc/hosts
### Task 04 -  Last lines of a file
4-lastlines > Script that displays the last 10 lines of /etc/passwd
### Task 05 - I'd prefer the first ones actually
5-firstlines > Script that displays the first 10 lines of /etc/passwd
### Task 06 - Line #2 
6-third_line > Script that displays the third line of the file iacta.
### Task 07 - It is a good file that cuts iron without making a noise 
7-file > Script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
### Task 08 - Save current state of directory
8-cwd_state > Script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
### Task 09 - Duplicate last line 
9-duplicate_last_line > Script that duplicates the last line of the file iacta
### Task 10 - No more javascript 
10-no_more_js > Script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
### Task 11 - Don't just count your directories, make your directories count 
11-directories > Script that counts the number of directories and sub-directories in the current directory.

- The current and parent directories should not be taken into account
- Hidden directories should be counted
### Task 12 - What’s new
12-newest_files > Script that displays the 10 newest files in the current directory.

Requirements:

- One file per line
- Sorted from the newest to the oldest
### Task 13 - Being unique is better than being perfect
13-unique > Script that takes a list of words as input and prints only words that appear exactly once.

- Input format: One line, one word
- Output format: One line, one word
- Words should be sorted
### Task 14 - It must be in that file
14-findthatword > Script that displays lines containing the pattern “root” from the file /etc/passwd
### Task 15 - Count that word
15-countthatword > Script that displays the number of lines that contain the pattern “bin” in the file /etc/passwd
### Task 16 - What's next?
16-whatsnext > Script that displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
### Task 17 - I hate bins 
17-hidethisword > Script that displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.
### Task 18 - Letters only please
18-letteronly > Script that displays all lines of the file /etc/ssh/sshd_config starting with a letter.

- include capital letters as well
### Task 19 - A to Z
19-AZ > Script that replaces all characters A and c from input to Z and e respectively.
### Task 20 - Without C, you would live in hiago 
20-hiago > Script that removes all letters c and C from input.
### Task 21 - esreveR
21-reverse > Script that reverses its input.
### Task 22 - DJ Cut Killer
22-users_and_homes > Script that displays all users and their home directories, sorted by users.

- Based on the the /etc/passwd file
