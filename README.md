# LinuxCustomShell-C

__This repository was initially an assignent that I was assigned while studying an Operating Systems Course in University. The assignment was to create a simple linux shell as per the assignment instrutions which requiered me to implement some of my own builtin CL commands for Linux using fork() and exec().__



## List of Commands initially made:
  - `cd` : **C**hange **D**irectory command [identical to the bash cd command].
  - `pwd` : **P**rint **W**orking **D**irectory command [identical to the basd pwd command].
  - `history` : Displays the last 10 executed commands by the user starting form the most-recently executed one.
  - `!!` : Executes the most recent command executed.
  - `!n` : Excutes the nth-last command executed.
  - `exit` : Exits the shell.
  - `help` : Command for displaying the information on various commands.
  - `Ctrl + C` : Shell catches this signal and executes the hel command.
  

## REFERENCES:
	- valgrind.org to debug or memory leaks etc.
	- man7.org/linux to access the manual for c system call for commands such as read(),write(),exec(),fork(),sigaction(), etc used in implementation of the shell.
