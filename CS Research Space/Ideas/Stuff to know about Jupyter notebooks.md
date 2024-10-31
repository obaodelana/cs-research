### Difference between `!` and `%`
The latter sends commands to Jupyter Notebook to execute, while the former sends the command to the shell to run.

Typing `%cd some_dir` affects later commands, while `!cd some_dir` runs in a shell, and returns back to Jupyter, effectively doing nothing.