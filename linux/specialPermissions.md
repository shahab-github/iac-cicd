umask is a command in Unix and Unix-like operating systems that sets the default permissions for newly created files and directories. It works by subtracting the specified mask from the default permissions

setgid (Set Group ID) is a permission similar to setuid, but it applies to executable files at the group level in Unix and Unix-like operating systems. When the setgid permission is set on an executable file, the program will run with the privileges of the group that owns the file rather than the group of the user who is executing it.

setuid (Set User ID) is a permission that can be assigned to an executable file in Unix and Unix-like operating systems. When the setuid permission is set on an executable file, the program will run with the privileges of the file's owner rather than the user who is executing it. This is often used for programs that need elevated privileges to perform certain tasks, such as system administration tasks.

The sticky bit is a permission in Unix and Unix-like operating systems that can be set on a directory. When the sticky bit is set on a directory, only the owner of a file within that directory can delete or rename the file, even if other users have write permissions on the same directory.
