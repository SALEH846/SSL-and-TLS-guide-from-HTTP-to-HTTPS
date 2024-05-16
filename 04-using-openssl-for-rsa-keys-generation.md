Generate RSA key using openssl
```bash
openssl genrsa
```

Generated encrypted private key
```bash
openssl genrsa -aes256
```
AES256 algorithm is used for encrypting the private key.
We can des3 like that, for example:
```bash
openssl genrsa -des3
```

Generate an encrypted RSA key and save it to a file
```bash
openssl genrsa -aes256 -out <nameOfFile>.pem
```

Extract public key from private key
```bash
openssl rsa -in <nameOfPrivateKeyFile>.pem -outform PEM -pubout -out <nameOfPublicKeyFile>.pem
```

By default, the length of generated key is 2048 bits. You can generate keys of different lengths.
```bash
openssl genrsa 4096
```