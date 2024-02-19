# Creating Linux Users with / without Home directories

- Create User **without** a Home Directory

        useradd testuser

        passwd testuser

- Create user **with** home Directory

        useradd -m testuser

- Create a user **with custom** home directory

        useradd -m -d /mnt/testuser testuser

- Change user directory of an existing user

        usermod -d /opt testuser

- delete a user

        userdel testuser -r # -r for deleting home dir

