Why Can't a Normal User chown a File:
Changing ownership (chown) requires superuser privileges.
Normal users don't have the necessary permissions to change ownership of files they don't own.

Running a Command with Root Privileges:
Use sudo followed by the command you want to run with elevated privileges.
Example: sudo ls /root (runs ls /root with superuser privileges)

Changing User ID or Becoming Superuser:
Use the su command followed by the username to switch to another user.
Use sudo -i or sudo su to become the superuser.
