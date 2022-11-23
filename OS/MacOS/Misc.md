### Configure Touch ID for sudo
1. Set the privileges for the /etc/pam.d/sudo file to "Read & Write" for everyone
2. Edit the file and add the following line below the comment
   ``` shell
   auth       sufficient     pam_tid.so
```
3. Save the file and change the privileges back to "Read Only " for everyone