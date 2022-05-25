# Command Line Syntax

As the shell input is read, it follows a sequence of operations, ignoring comments (`#`) and seperating the input into words and operations

1. Read Input
    2. Divide Input
        - Ignore comments (comments start with `#`)
    3. Apply Quoting
        - Ignore literal translation of something we are sending to the interpreter
    4. Parse Into Commands
    5. Apply Redirection
    6. Wait for next status
        - was the command successfull or not
8. **Display Output**


Command Options
`ls -a`
`ls -h`

To view all command options, use the `man` command
`man ls`

