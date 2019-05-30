# Useful TAR commands
1. ssh -l remote_user 192.192.192.192 "cd /var/www/ && tar cf - remoteFolderName" > localTarName.tar

Connect to remote server cd to directory and download remote dir to local as tar file

2. encrypt file
```
openssl aes-256-cbc -a -salt -in enc.tar.gz -out enc.tar.gz.aes256
```

3. decrypt file
```
openssl aes-256-cbc -d -a -in enc.tar.gz.aes256 -out decrypted.tar.gz
```
