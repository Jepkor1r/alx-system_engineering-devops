SHELL REDIRECTIONS

1. Standard Input (stdin):

Symbol: <
Usage: Redirects input from a file to a command.
Example: command < input file

2. Standard Output (stdout):

Symbol: >
Usage: Redirects output from a command to a file, overwriting the file if it exists.
Example: command > output file

3. Append to a File:

Symbol: >>
Usage: Appends the output of a command to a file.
Example: command >> output file

4. Redirecting Standard Error (stderr):

Symbol: 2>
Usage: Redirects error output from a command to a file.
Example: command 2> error file

5. Redirecting Both Output and Error:

Symbol: &>
Usage: Redirects both standard output and standard error to a file.
Example: command &> output and error file

6. Combining Commands:

Symbol: |
Usage: Passes the output of one command as input to another.
Example: command1 | command2

7. Here Document:

Syntax: <<EOF ... commands ... EOF
Usage: Allows input to be passed to a command block.
Example:
```bash
cat <<END
Line 1
Line 2
END
```

8. Here String:

Syntax: command <<< "string"
Usage: Sends a string as input to a command.
Example: echo "Hello" <<< cat
NUL Device:

Symbol: /dev/null
Usage: Discards output or input.
Example: command > /dev/null (silencing output)

9. Command Substitution:

Syntax: $(command)
Usage: Replaces the command substitution with the output of the enclosed command.
Example: echo "Today is $(date)"

10. File Descriptor Duplication:

Syntax: command 2>&1
Usage: Redirects standard error (file descriptor 2) to standard output.
Example: command > output file 2>&1
