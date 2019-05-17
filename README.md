# LinuxCustomShell-C

__This repository was initially an assignent that I was assigned while studying an Operating Systems Course in University. The assignment was to create a simple linux shell as per the assignment instrutions which requiered me to implement some of my own builtin CL commands for Linux using fork() and exec().__


## Programming Language

> ### C
	
	
## Operating System 
>  ### Ubuntu 18.04 LTS
	
	
## Setup:
 1. __Clone repository__ on a Linux system.
 2. __Navigate__ to the root directory of the repository.
 3. __Build__ executeable object [.o file] using the command:
 	> ` make shell `
 4. __Execute__ commands.
 
 
## List of Commands initially made:
  - `cd` : **C**hange **D**irectory command [identical to the bash cd command].
  - `pwd` : **P**rint **W**orking **D**irectory command [identical to the basd pwd command].
  - `history` : Displays the last 10 executed commands by the user starting form the most-recently executed one.
  - `!!` : Executes the most recent command executed.
  - `!n` : Excutes the nth-last command executed.
  - `exit` : Exits the shell.
  - `help` : Command for displaying the information on various commands.
  - `Ctrl + C` : Shell catches this signal and executes the hel command.
  
  
## Usage:
   
   | Command | Arguments | Syntax (Example) | Description |
   | --- | --- | --- | --- |
   | ` cd <dir> ` | __Directory name__ | ` cd myDirectory ` | Changes current directory to the one specified. [` .. ` for previous directory] |
   | ` pwd ` | __no arguments__ | ` pwd ` | Prints current workin directly to console |
   | ` !! ` | __no arguments__ | ` !! ` | Executes the last executed command (Only executes the last __SUCCESSFULLY__ executed command) |
   | ` !n ` | __Last nth command__ | ` !3 ` | Executes the last nth command |
   | ` help ` | __no arguments__ or __command name__ | ` help ` or ` help cd ` | if no argument provided gives description of built-in commands. If argument is provided gives information on that specific command |
   | ` exit ` | __no arguments__ | ` exit ` | prints an exit message and eits the shell |
   
   
 ##### If you have suggestions for more commands feel free to send me an email at sg8797@gmail.com .
 
 ##### If you would like to work with me on this project further please contact me at my email address below.
 

## REFERENCES:
	- valgrind.org to debug or memory leaks etc.
	- man7.org/linux to access the manual for c system call for commands such as read(),write(),exec(),fork(),sigaction(), etc used in implementation of the shell.

### Documentation By :-
> ### Siddharth Gupta
