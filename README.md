# KEYFILE_AES
Encrypt and decrypt files using AES (Advanced Encryption Standard)

## Getting Started
Install Python

Install package manager pip, wheel, and pycryptodome by typing in the following command lines in cmd
```bash
python -m pip install --upgrade pip
pip install wheel
pip install pycryptodome
```
## Usage

### ENCRYPT_IT

Run *FINAL_ENCRYPT_IT_00.py* or *FINAL_ENCRYPT_IT_00.exe* (for the ones who doesn't want to install python)

Follow the instruction given by the program

Key file *KEYIV.key* and directory *2ENCRYPTED* and *3DECRYPTED* is formed on the current directory

The encrypted files are located in *2ENCRYPTED* and the decrypted files are located in *3DECRYPTED*

Verify the files in *3DECRYPTED* to make sure it is identical to the original files in *1ORIGINAL*

Send the encrypted files in *2ENCRYPTED* with the key file generated by the program to the recipient.

It is recommended to send the two files separately via two different authorities for privacy and security reasons.

### DECRYPT_IT

Run *FINAL_DECRYPT_IT_00.py* or *FINAL_DECRYPT_IT_00.exe* (for the ones who doesn't want to install python)

Follow the instruction given by the program

Directory *2DECRYPTED* with the decrypted files is formed in the current directory

## Technologies

The project is created using *Python 3.7* and it involves the process of...
* Using AES (Advanced Encryption Standard) to encrypt / decrypt files
* Generating random value using Crypto package
* Formulating an executable file from python script
* Making basic system calls
* Parsing .txt, .py, .key files


## Authors

* **EuiSuh (John) Jeong** - *Initial work* - [website](https://web2.qatar.cmu.edu/~ejeong/)
* **Qian (Ivy) Lou** - *Beta Testing*

## References
* https://nitratine.net/blog/post/python-encryption-and-decryption-with-pycryptodome/
* https://stackoverflow.com/questions/41980931/image-encryption-and-decryption-using-pycrypto

