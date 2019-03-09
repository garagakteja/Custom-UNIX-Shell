# Custom-UNIX-Shell : Command Execution ('exec' and its variations), I/O Redirection('<','>') and Pipes('|').
Customised build of the UNIX shell.

Part 1: Command Execution ('exec' command at its variants)
Implement basic command execution by filling in the code inside of the runcmd function. 

Part 2: I/O Redirection ('<' and '>')
Extension of the shell to handle input and output redirection. Programs will be expecting their input on standard input and will write to standard output, so we open the file and then replace standard input or output with that file.

Part 3: Pipes ('|')
Addition of the ability to pipe the output of one command into the input of another. The code for the | case of the switch statement in runcmd to do this.

Final goal is to implment a working model of a full pipeline such as:
sktg> cat /usr/share/dict/words | grep cat | sed s/cat/dog/ > doggerel.txt
sktg> grep con < doggerel.txt

[NOTE : The skeletal code for shell.c is adapted from the xv6 shell]




