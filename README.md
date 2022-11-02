0x16. C - Simple Shell
About

The shell is the Linux command line interpreter. It provides an interface between the user and the kernel and executes programs called commands. For example, if a user enters ls then the shell executes the ls command.

This project, simple_shell, is a custom implementation of a simple UNIX shell as a requirement to complete the first sprint in the ALX - Holberton school 12-month SE program. Taking a minimalistic approach, the following functions have been implemented: access, execve, exit, fork, free, fstat, getline, malloc, perror, signal, stat, wait, write.
Table of Contents

    About
    File Descriptions
    Requirements
    More Info and Examples
        Installation
        Examples
    Mandatory Tasks
    Advanced Tasks
    Bugs
    Authors
    License

File Descriptions

    AUTHORS - It lists the contributors of this project
    man_1_simple_shell - The Manual describing usage of the simple_shell
    shell.h - The header file used in this project

Requirements
General

    Allowed editors: vi, vim, emacs
    All files were compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
    Betty coding style is followed.
    The simple shell has no known memory leaks

More Info and Examples
Installation

Designed to run on Ubuntu 20.04 LTS, the simple_shell can be installed as follows:

    Clone the current repository with the command: git clone "https://github.com/stephenmakenziwaweru/simple_shell.git"
    cd in to the cloned directory: cd simple_shell
    Create an executable using: gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
    Run the executable either in interative mode ./hsh or non-interactive mode echo "pwd" | ./hsh

Examples

Example of error with sh:

$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$

Same error with our program hsh:

$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$

Mandatory Tasks

    0. README, man, AUTHORS
    1. Betty would be proud
    2. Simple shell 0.1
    3. Simple shell 0.2
    4. Simple shell 0.3
    5. Simple shell 0.4
    6. Simple shell 1.0
    7. What happens when you type ls -l \*.c in the shell

Advanced Tasks

    8. Test suite
    9. Simple shell 0.1.1
    10. Simple shell 0.2.1
    11. Simple shell 0.4.1
    12. Simple shell 0.4.2
    13. setenv, unsetenv
    14. cd
    15. ;
    16. && and ||
    17. alias
    18. Variables
    19. Comments
    20. help
    21. history
    22. File as input

