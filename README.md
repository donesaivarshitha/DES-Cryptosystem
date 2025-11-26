# DES Cryptosystem

This project provides a simple and interactive Python program that demonstrates how the DES (Data Encryption Standard) algorithm works using the PyCryptodome library.

It allows users to:

1. Encrypt plaintext using DES
  
2. Decrypt ciphertext using DES
   
3. Understand padding, keys, and how ECB mode functions

Features:

✔ Encryption

• User enters an 8-byte DES key (required by the DES standard)

• Plaintext is padded automatically to match 8-byte block size

• Output ciphertext is displayed in hexadecimal format for readability

✔ Decryption

• User enters the same 8-byte key

• User inputs ciphertext hex string

• Program decrypts and removes padding, restoring the original message

✔ Error Handling

• Invalid key length (must be exactly 8 characters)

• Invalid ciphertext hex input

• Wrong key or corrupted ciphertext (padding failure)
