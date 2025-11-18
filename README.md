# OPEN-SOURCE-EX-4
# Aim:
To create a secure group-collaborative directory /common/admin where only members of the admin group can access and where all files inherit the group ownership admin.
# Procedure:
1. Log in to the Linux system with root or administrative privileges.
2. Create a new directory structure starting with /common and then create the admin subdirectory inside it.
3. Change the group ownership of the /common/admin directory so that it belongs to the admin group.
4. Set directory permissions so that only users who are members of the admin group can access, read, and write inside /common/admin.
Ensure that other users do not have any access.
5. Enable the “setgid” permission on the /common/admin directory.
6. Verify permissions and group ownership of the directory to ensure correct configuration.
   
# Output:
<img width="729" height="345" alt="image" src="https://github.com/user-attachments/assets/def6c29d-9aaa-413b-955f-f81580efaa62" />

# Result:
The directory /common/admin was successfully created.
Its group was set to admin, and permissions were configured so that only members of the admin group can access it.
The setgid bit ensures that any file or directory created inside /common/admin automatically inherits the admin group ownership.
