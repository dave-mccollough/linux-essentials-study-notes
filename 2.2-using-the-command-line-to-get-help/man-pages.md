# Man Pages

Traditional package documentation for application usage

Manual pages are the traditional form of software documentation on UNIX systems.  They are included with the software they document.

The man page for a particular command is invoked by preceding the command with `man`
- `man COMMAND`
- `man ls`

## Sections of the man command

**Name:**
Program or function name(s) followed by a terse description of the functionality.

**Synopsis:** 
A short overview of available options.

**Description:**
Detailed information of arguments and options.

**Examples:**
Common usage examples

**Exit Status**
- Return Code once a command is run
 - 1: If ok
 - 2: Minor problems
 - 3: If serious trouble
 `ls`
`echo $?`
`0`
