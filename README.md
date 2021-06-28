# FileEncryptor

This is a simple tool to encrypt/decrypt files using python cryptography library.

### Requirements:

    cryptography > 2.1.4

### How to run:

    python3 main.py <OPTION>

    OPTION: 
        e : encryption
        d : decryption

### Folder details:

    input: All files under this folder will be encrypted/decrypted based on operation
    output: Output files from ecryption or decryption


For Encryption you either provide a 44 character key inside '*input*' folder with file name '*key.txt*'. If it is not provided, the script will generate a key and use it.

For Decryption '*key.txt*' is mandatory in '*input*' folder
