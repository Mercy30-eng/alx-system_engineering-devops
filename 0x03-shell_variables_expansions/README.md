##Shell variable expansions
/**
 *Simple shell tasks
*/

####0-alias
Creates an alias in the Bash shell.
Specifically, it creates an alias for the ls command, which is commonly used to list files and directories. 
Aliases in the shell are typically used to create shortcuts for commands or to customize the behavior of existing commands. However, it's crucial to exercise caution when creating aliases, especially when they modify the behavior of commonly used commands like
 ls.

####1-hello_you
The script uses the echo command to display the text "hello" followed by the value of the $USER environment variable, which
typically represents the current user's username.

####2-path
export PATH=$PATH:/action: This line appends the /action directory to the existing PATH environment variable. The export command 
makes the PATH variable available to child processes of the current shell.

####3-paths
It calculates the number of directories in the PATH environment variable and then adds 1 to the count. The final result is printed to the standard output. This can be useful for various system administration and scripting tasks.performs the following operations:

echo $PATH: Prints the value of the PATH environment variable.
|: Pipes the output of the previous command to the next command.
grep -o ":/": Searches for the pattern ":/" in the output and prints each match on a new line.
wc -l: Counts the number of lines in the output, which corresponds to the number of directory separators (":/") in the PATH.
+ 1: Adds 1 to the count obtained from the previous command. 

####4-global_variables
The printenv command is used to print the current environment variables and their values.
you can quickly view the environment variables set in the current shell environment, which can be useful for debugging, troubleshooting, or understanding the configuration of the system.

####5-local_variables
The set command, when used without any options or arguments, prints all shell variables and functions.When this script is run, it will output a list of all the shell variables and functions that are currently set in the shell environment.

####6-create_local_variable
When this script is executed, it defines the variable BEST with the value "School". This variable can then be used within the script or accessed by other commands or scripts that are executed subsequently.

####7-create_global_variable
By using the export command, the variable BEST is made available to child processes of the current shell.

####8-true_knowledge
