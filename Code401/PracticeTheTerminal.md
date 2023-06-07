# Practice in the Terminal


**A command line:** text based interface that allows us the input of commands that will be executed on OS's Kernel level.

**Shell:** Part of OS that decides how it's going to react and executes commands. There are various shells, each nuanced in its own way. Most common shells are - Bash (Bourne again shell), Zsh, PowerShell, etc. 

### **Interesting facts:** 

* Everything is a file. Including directories.
* Linux is an Extensionless System. Linux system ignores the extension and looks inside the file to determine what type of file it is.
* Linux is case sensitive.   
* Spaces in directory names must be avoided to prevent confusion. 
* There's a command line edditor - vi. If needed: vi hello.js
* Linux permissions dictate 3 things you may do with a file, read, write and execute. **r - Read**, **w - Write**, **x - Execute**.
* There are filters in Linux system. It's is a program that accepts textual data and then transforms it in a particular way. 
* We are able to redirect information through Piping and Redirection. Also, there are 3 streams of information: 

1) STDIN (0) - Standard input (data fed into the program)

2) STDOUT (1) - Standard output (data printed by the program, defaults to the terminal)

3) STDERR (2) - Standard error (for error messages, also defaults to the terminal)

* We can also redirect TO a file and FROM a file. 

Ways of redirection: 

    >  Save output to a file.
   
    >> Append output to a file.
     
    <  Read input from a file.   
     
    2> Redirect error messages.
     
    |  Send the output from one program as input to another program.

### **Important commands:**

* **pwd** - (Print working directory), 
* **ls** - (listing of the current location /[options][location]) To show **hidden** files, use **-a** option, 
* **~(tilde)** - This is a shortcut for your home directory.
* **. (dot)** - This is a reference to your current directory.
* **.. (dotdot)** - This is a reference to the parent directory.
* **cd [location]** - change directory.
* **file [path]** - check the file's type.
* **man <command to look up>** - calls manual for a specified command.
* **mkdir [options] <Directory>** - creates a directory. **-p** option creates parent directories. *-v* option announces each step of directory creation. *-pv* is possible.
* **rmdir [options] <Directory>** - remove directory. For **non-empty** directory use **-r** option.
* **touch [options] <filename>** - create a blank file.   
* **cp [options] <source> <destination>** - copy a file or directory.  
* **ls -l [path]** - view permissions
* **chmod [permissions] [path]** - Change permissions on a file or directory.   
* **head [-number of lines to print] [path]** - prints a specified number of first lines from a file. 
* **tail [-number of lines to print] [path]** - opposite to Head.
 * **cat [path]** - show the outpit of a specified file.
 
### Absolute and Relative Paths
* Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )
* Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.
