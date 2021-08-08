# Linux Shell using C
Made our own custom shell using C in Linux 

Below is the list of commands implemented  

| Syntax              | Meaning                                                                                                                    |
|---------------------|----------------------------------------------------------------------------------------------------------------------------|
| command             | execute the command and wait for the command to finish, print error message if the command is invalid                      |
| command > filename  | redirect stdout to file “filename”. If the file does not exist create one,otherwise,  overwrite the existing file          |
| command >> filename | If the filename already exists append the stdout output, otherwise, create a new file                                      |
| 1>filename          | redirect stdout to filename                                                                                                |
| 2>filename          | redirect stderr to filename                                                                                                |
| 2>&1                | redirect stderr to stdout                                                                                                  |
| command < filename  | use file descriptor 0 (stdin) for filename. If command tries to read from stdin,   effectively it will read from filename. |
| |                   | pipe command                                                                                                               |
| exit                | exit from the shell program                                                                                                |

Made by:
Prashant Tiwari, Mansi Gupta, Chandranath Hazra
