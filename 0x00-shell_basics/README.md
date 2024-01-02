General
RTFM:

Meaning: "Read The Fine Manual" or a less polite variation. It's a humorous way of telling someone to read the documentation.
Example: "Before asking for help, RTFM to see if your question is answered there."
Shebang:

Definition: It's the #! at the beginning of a script, followed by the path to the interpreter. It specifies the scripting language for the script.
Example: #!/bin/bash at the top of a Bash script.
Shell:

Definition: A shell is a command-line interface that allows users to interact with the operating system. It interprets commands and executes them.
Example: Bash, Zsh, or PowerShell.
Terminal vs. Shell:

Difference: A terminal is a program that provides a text-based interface, while a shell is the command interpreter that processes and executes commands.
Example: In a terminal (like Command Prompt), you interact with a shell (like CMD).
Shell Prompt:

Definition: It's the text or symbol displayed in the terminal, indicating that the shell is ready to accept commands.
Example: The classic $ or > prompt.
Navigation
cd, pwd, ls:

cd: Changes the current directory.
pwd: Prints the current working directory.
ls: Lists files and directories in the current directory.
Example: cd Documents, pwd, ls -l.
Filesystem Navigation:

Definition: Moving through directories using commands like cd and navigating with relative or absolute paths.
Example: cd /home/user/Documents.
. and .. Directories:

Definition: . represents the current directory, .. represents the parent directory.
Example: cd .. moves up one directory.
Working Directory:

Definition: The current directory where commands are executed. pwd prints it, and cd changes it.
Example: pwd might output /home/user.
Root Directory:

Definition: The top-level directory in a filesystem.
Example: Represented by /.
Home Directory:

Definition: The default directory for a user. Represented by ~.
Example: cd ~ takes you to your home directory.
Hidden Files:

Characteristics: Start with a dot (.) and are not displayed by default.
Example: .config is a hidden directory.
cd - Command:

Definition: Switches to the previous working directory.
Example: cd - might switch you back to the directory you were in before the last cd command.
Looking Around
ls, less, file:

ls: Lists files and directories.
less: Allows you to view text files interactively.
file: Determines a file's type.
Example: ls -l, less readme.txt, file document.pdf.
Using Options and Arguments:

Options: Modify command behavior (e.g., -l in ls -l).
Arguments: Provide input (e.g., file names in ls file1 file2).
ls Long Format:

Definition: A detailed listing showing file details.
Example: ls -l.
A Guided Tour
ln Command:

Definition: Creates links between files.
Example: ln -s sourcefile linkname creates a symbolic link.
Important Directories:

Examples: /bin (essential binaries), /home (user home directories), /etc (system configuration).
Symbolic Link vs. Hard Link:

Symbolic Link: Points to another file by name.
Hard Link: Points to the same inode as another file.
Difference: Deleting the original file affects symbolic links; hard links share the same data.
Manipulating Files
cp, mv, rm, mkdir:

cp: Copies files.
mv: Moves or renames files.
rm: Removes files.
mkdir: Creates directories.
Examples: cp file1 file2, mv oldfile newfile, rm unwanted.txt, mkdir newfolder.
Wildcards:

Definition: Symbols like * and ? that represent multiple characters.
Example: *.txt matches all text files.
Working with Commands
type, which, help, man:

type: Shows how a command name is interpreted.
which: Shows the full path of executable commands.
help: Provides help for shell-builtins.
man: Displays the manual for a command.
Examples: type ls, which python, help cd, man ls.
Alias:

Definition: A custom shorthand for a command or sequence of commands.
Example: alias ll='ls -l'.
help vs. man:

help: Provides help for shell-builtins.
man: Displays the manual for a command.
Usage: help cd for shell built-ins, man ls for external commands.
Reading Man Pages
Reading a Man Page:

Usage: man command (e.g., man ls).
Sections: Manual pages are organized into sections.
Man Page Sections:

User Commands (1): Executable programs or shell commands.
System Calls (2): Functions provided by the kernel.
Library Functions (3): Functions within program libraries.
Keyboard Shortcuts for Bash
Common Shortcuts:

Ctrl+C: Interrupt current process.
Ctrl+D: Log out or end session.
Ctrl+Z: Suspend a process.
Ctrl+A: Move to the beginning of the line.
Ctrl+E: Move to the end of the line.
LTS
LTS:

Meaning: Long-Term Support.
Explanation: A version of software that receives support and updates for an extended period, often used in stable environments.
Example: Ubuntu LTS releases are supported for five years.
