# simple_unix_shell
A shell interface that can execute command line commands in a seperate process by utilizing the UNIX fork() system call. 
The shell has a history feature when "!!" is entered, which will execute the most recent command. Input and output redirection 
operators, '<' and '>', are also supported to read or write from .txt files. The output of a command is also able to be an
input for another command, using the '|' pipe operator. 
