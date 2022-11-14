Simple Shell Project
This repo contains my implementation of the ALX SE Program Project 0x16. The project is a simple shell which should work exactly like a normal terminal or command prompt when run on a computer.

Getting Started
Clone the Repo to your local machine
cd into the repo directory
Run the following code in your terminal to compile
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh 
Note that you should have a valid C compiler installed, for this to work. In this example we have used gcc but you can replace it with clang or any other compiler available on your machine.

Then you can run in interactive mode like ./hsh
The code above is for a unix type machine, for windows, the compilation will produce a hsh.exe which you can click on

Or in non interactive mode like echo "/bin/ls" | ./hsh
Contributing Guide
[Fix] - Represents a bug fix, format - [Fix]: Bug Fixed
[Betty] - Represents a fix for code style compliance, format - [Betty]: Trailing whitespace
[Feat] - Represents a new file, or function that adds a feature of the shell, format - [Feat]: Enable printing errors
[Update] - Represents a generic update(Usually for testing).
