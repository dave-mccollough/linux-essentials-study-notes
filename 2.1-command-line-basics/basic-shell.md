# Basic Shell

The standard Linux Shell (BASH) is both a command line interpreter and programming language

## Command Prompt
- Short test string at the beginning of the command line.
- Typically shows the current user, host and working directory
    - `[USER@HOST_NAME ~]$`
- If you are the Root user the command prompt will be a `#`:
       - `[USER@HOST_NAME ~]#`
- The command prompt can be modified to show more or less information
- Input from the command line is sent to the interpreter to be parsed and executed

## Commands
- Commands are entered as text at the command line prompt
- They are parsed by the interpreter and executed by the shell as a process
- Commands are entered as text into the input stream known as Standard In (STDIN)
- These commands adhere to a syntax defined by the interpreter or the current shell

## Command Output
- The output of the entered command is displayed on the the line following the command itself
- Output will be sent to one of two streams
    - Standard Out (STDOUT)
        - Display
        - Redirection or pipeline
    - Standard Error (STDERR) 
        - Display
        - Redirection or pipeline

- **Keyboard Input** -> STDIN -> **Process** -> STDOUT/STDERR -> *Display**

-