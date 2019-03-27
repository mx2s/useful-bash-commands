# Useful TAR commands
1. ssh -l remote_user 192.192.192.192 "cd /var/www/ && tar cf - remoteFolderName" > localTarName.tar
Connect to remote server cd to directory and download remote dir to local as tar file
