# lock & unlock a Linux user using root

resource : [CLICK HERE](https://www.howtouselinux.com/post/linux-command-lock-a-user-account-in-linux)
- Lock and Unlock using ```passwd``` command

        #lock
        passwd -l testuser

        #unlock
        passwd -u testuser

     locking the password does not disable the user account entirely; it only prevents the user from logging in using a password. They may still be able to log in using other authentication methods, such as SSH keys or other authentication mechanisms depending on the system configuration.

- Lock / unlock the user using ``usermod``

        #lock
        sudo usermod --lock username
        sudo usermod -L username

        #unlock
        sudo usermod --unlock username
        sudo usermod -U username


This command completely locks the user itself.




