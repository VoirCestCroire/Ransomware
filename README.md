Encrypting current directory using symmetrical authenticated cryptography with Fernet https://cryptography.io/en/latest/fernet/
Fernet is built on top of a number of standard cryptographic primitives. Specifically it uses:
AES in CBC mode with a 128-bit key for encryption; using PKCS7 padding.
HMAC using SHA256 for authentication.
