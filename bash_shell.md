# Cheatsheet - bash shell
###### by Jacobs Official Informational Notes on Tech


## Basics
Cancel a running command `ctrl-c`

Exit current shell session or logout of server `ctrl-d`

Tab completion filters or auto completes commands

clear your terminal with `ctrl-l` same as `clear`

## Movement
Move to the beginning of a line `ctrl-a`

Move to the end of a line `ctrl-e`

Move forward by one word `alt-f`

Move backward by one word `alt-b`

## Quality of Life
List your previous shell commands `history`

Reverse search through your previous shell commands `ctrl-r`

Run your previous command with `!!`  
> Example  
If you run a command and forget to `sudo`    
Run `sudo !!` to run the same command with sudo privileges

When writing a long command use `ctrl-x-e` to open a string buffer for easier typing

paste the arguments of your last successful command `alt - .` (alt + period)
> Example  
If we run `echo dog`  
using `alt - .`  
we can reuse our last argument `dog` and print to the terminal


## Killing and Yanking (cutting and pasting)
`ctrl-k` cut all text after the cursor

`ctrl-u` cuts all text before the cursor

`ctrl-w` cuts by words before the cursor

`ctrl-y` pastes the text

###### References
https://www.youtube.com/watch?v=V8EUdia_kOE  
https://www.youtube.com/watch?v=C-AQAJXdoS8
