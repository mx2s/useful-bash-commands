# Useful CRYPTO commands
1. tar cz folder_to_encrypt | \
      openssl enc -aes-256-cbc -e > out.tar.gz.enc
    
Encrypto folder with password (in tar file)

2. openssl enc -aes-256-cbc -d -in out.tar.gz.enc -pass pass:'1234' | tar xz

Decrypt tar file with password
