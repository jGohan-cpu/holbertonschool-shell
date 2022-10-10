# HolbertonSchool-Shell / Shell, I/O Redirections And Filters

### Explanation Of Exercises
* File 0 - the "echo "Hello, World"" command was used to write a script that prints “Hello, World”, followed by a new line to the standard output.
* File 1 - the "echo "\"(Ôo)'"" command was used to write a script that displays a confused smiley "(Ôo)'.
* File 2 - the "cat /etc/passwd " command was used to display the content of the /etc/passwd file.
* File 3 - the "cat /etc/passwd /etc/hosts " command was used to display the content of /etc/passwd and /etc/hosts.
* File 4 - the "tail -10 /etc/passwd" command was used to display the last 10 lines of /etc/passwd.
* File 5 - the "head -10 /etc/passwd" command was used to display the first 10 lines of /etc/passwd.
* File 6 - the "head -3 iacta | tail +3" command was used to write a script that displays the third line of the file iacta.
* File 7 - the "echo "Best School" > "\\*\\\\'\"Best School\"\\'\\\\*\$\\?\\*\\*\\*\\*\\*:)" " command was used to write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
* File 8 - the "ls -la > ls_cwd_content" command was used to write a script that writes into the file ls_cwd_content the result of the command ls -la. 
* File 9 - the "cat iacta | tail -n 1 >> iacta" command was used to write a script that duplicates the last line of the file iacta.
* File 10 - the "find . -name '*.js' -type f -delete " command was used to write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
* File 11 - the "find . -type d|tail -n +2|wc -l" command was used to write a script that counts the number of directories and sub-directories in the current directory.
* File 12 - the "ls -t |head -n 10" command was used to create a script that displays the 10 newest files in the current directory.
* File 13 - the "sort |uniq -u" command was used to create a script that takes a list of words as input and prints only words that appear exactly once.
* File 14 - the "cat /etc/passwd | grep "root"" command was used to display lines containing the pattern “root” from the file /etc/passwd.
* File 15 - the "cat /etc/passwd | grep "bin" -c" command was used to display the number of lines that contain the pattern “bin” in the file /etc/passwd.
* File 16 - the "grep -iA 3 "root" /etc/passwd" command was used to display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
* File 17 - the "grep -v "bin" /etc/passwd" command was used to display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
* File 18 - the "grep '^[[:alpha:]]' /etc/ssh/sshd_config" command was used to display all lines of the file /etc/ssh/sshd_config starting with a letter.
* File 19 - the "tr A Z | tr c e" command was used to replace all characters A and c from input to Z and e respectively.
* File 20 - the "tr -d Cc" command was used to create a script that removes all letters c and C from input.
* File 21 - the "rev" command was used to write a script that reverse its input.
* File 22 - the "cut -d : -f 1,6 /etc/passwd | sort" command was used to write a script that displays all users and their home directories, sorted by users.
* File 23 - the "find . -depth -empty -printf %f'\n'" command was used to write a command that finds all empty files and directories in the current directory and all sub-directories.
* File 24 - the "find . -depth -type f -name "*.gif" -printf %f'\n'| LC_ALL=C sort -f | rev | cut -c 5- | rev" command was used to write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.
* File 25 - the "echo $(cut -c -1 | tr -d '\n')" command was used to create a script that decodes acrostics that use the first letter of each line.
* File 26 - the "tail -n +2 | cut -f 1 | sort | uniq -c | sort -rn | cut -c 9- | head -11" command was used to write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
