- For templates use python `os.chroot` to chroot into a directory and execute necessary commands
- use getpass.getuser during `create` to make sure that the user is root (if template is enabled)