# Cascade-Cryptography
An Encryption, Decryption & BlindIndex Search bundle made with PHP.  
The purpose of this package is to help simplify the process of Cryptography using Sodium.  

The Cryptography.php file contains AEAD_XCHACHA20_POLY1305_IETF Encryption and Decryption methods capiable of cryptographically securing and decrypting a range of data types.  

Additionally, the Cryptography class offers methods to hash and salt passwords using the Argon2ID alogorithm.  

## Security Issues
> **Warning** 
For any security issue reports, please contact the author with the processed used for vulnerabilites discovered.
Do not report elsewhere. 

## General Issues
For all other issues with this file or bundle, please feel free to open a issue on Github or contact the author.

## Document_Notes
Created: 2021 12 22 - 01:45 GMT
Updated: 2022 07 12 - 02:03 GMT

## Development State 
[✔️] Encryption  
[✔️] Decryption  
[➖] Blind Index  
[➖] Unit Tests  
[❌] Asymmetric encryption  
[❌] Key Splitting  


## Features
### Encryption

### Decryption

### Blind Index

### Asymmetric encryption

### Key Splitting
Act of splitting key into parts for to mitigate full key compromise in use of encryption & Decryption.  

## Cipher Information  
### AEAD_XCHACHA20_POLY1305_IETF  
see https://doc.libsodium.org/secret-key_cryptography/aead  

#### Cipher Availability and interoperability  
- Key Size: 256 Bits  
- Nonce Size: 192 Bits   
- Block Size: 512 Bits  

#### Cipher Limitations  
Max Bytes for a single (Key, Nonce): No Practical limits (~2^64 Bytes).  
Max Bytes for a single Key: Up to 2^64* messages, no practical total size limits.  

#### Security Notes  
Sodium_bin2hex offers side-channel atteck attack mitigation.  
see https://owasp.org/www-pdf-archive/Side_Channel_Vulnerabilities.pdf
