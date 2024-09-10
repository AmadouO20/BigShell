# **Bigshell in C**

BigShell is a command language interpreter. Reads its input from standard input. Breaks the input into tokens: words and operators. Parses the input into commands.  Performs various expansions (separately) on different parts of each command, resulting in a list of pathnames and words to be treated as a command and arguments. Performs redirection and removes redirection operators and their operands from the parameter list. Executes a built-in, or executable file, giving the names of the arguments as positional parameters numbered 1 to n, and the name of the command as the positional parameter numbered 0. Optionally waits for the command to complete and collects the exit status

Parsed command-line input into commands to be executed, executed a variety of external commands (programs) as
separate processes, implemented a variety of shell built-in commands within the shell itself

Performed a variety of i/o redirection on behalf of commands to be executed, assigned, evaluated, and exported to the
environment, shell variables

Implemented signal handling appropriate for a shell and executed commands, managed processes and pipelines of
processes using job control concepts
