Minishell is a project from the 42 school. The task was to code a simple functionning shell based on bash's behaviors. I had to program a few builtin commands by myself and use execve to call other commands.

The list of builtin commands :
  --> export with no options;
  --> echo with option -n;
  --> env with no options;
  --> unset with no options;
  --> pwd with no options;
  --> cd with no options;
  --> exit with no options;

I display the prompt and manage the history with the termcaps library.
I used linked chain to manage command and their arguments.
