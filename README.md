# 0x16. C - Simple Shell
 **By Julien Barbier**
Project done in teams of 2 people (This team: Geda siraj Mohammed, Harriet Iluekhabho)

More Info
Output
This program have the exact same output as sh (/bin/sh) as well as the exact same error output.
The only difference is when printing an error, the name of the program will be equivalent to ./hsh (See below)
Example of error with sh:

$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$
Same error with this program hsh:

$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$

# Compilation
## This shell will be compiled this way:

`gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh`

