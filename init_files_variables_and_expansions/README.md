# HolbertonSchool-Shell / Shell, Init Files, Variables And Expansions

### Explanation Of Exercises
* Exercise 0 - the "alias ls="rm *"" command was used to create a script that creates an alias.
* Exercise 1 - the "echo hello $USER" command was used to create a script that prints hello user, where user is the current Linux user.
* Exercise 2 - the "export PATH=$PATH:/action" command was used to add /action to the PATH.
* Exercise 3 - the "echo $PATH | tr -s ':' '\n' | wc -l" command was used to create a script that counts the number of directories in the PATH.
* Exercise 4 - the "printenv" command was used to create a script that lists environment variables.
* Exercise 5 - the "set" command was used to create list all local variables and environment variables, and functions.
* Exercise 6 - the "BEST="School"" command was used to create a new local variable.
* Exercise 7 - the "export BEST="School"" command was used to create a new global variable.
* Exercise 8 - the "echo $(( 128 + $TRUEKNOWLEDGE ))" command was used to print the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
* Exercise 9 - the "echo $((POWER/$DIVIDE))" command was used to print the result of POWER divided by DIVIDE, followed by a new line.
* Exercise 10 - the "echo $(( $BREATH**$LOVE ))" command was used to convert a number from base 2 to base 10.
* Exercise 11 - the "echo $(( 2#$BINARY ))" command was used to display the result of BREATH to the power LOVE.
* Exercise 12 - the "echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"" command was used to convert a number from base 2 to base 10.
* Exercise 13 - the "printf '%.2f\n' $NUM" command was used to print all possible combinations of two letters, except oo.
* Exercise 14 - the "printf '%x\n' $DECIMAL" command was used to print a number with two decimal places, followed by a new line.
* Exercise 15 - the "tr 'A-Ma-mN-Zn-z' 'N-Zn-zA-Ma-m'" command was used to convert a number from base 10 to base 16.
* Exercise 16 - the "tr paste - - | cut -f1" command was used to  encode and decode text using the rot13 encryption. Assume ASCII.
* Exercise 17 - the "paste - - | cut -f1" command was used to print every other line from the input, starting with the first line.
* Exercise 18 - the "" command was used to add the two numbers stored in the environment variables WATER and STIR and prints the result.
