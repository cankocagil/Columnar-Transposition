# Cryptography Assembly

This repo contains Cryptography application using Assembly language. I implemented a simple encryption algorithm using two terminals. The input will be given from the first terminal, labeled “input terminal”, and an encrypted or de-crypted version of the input will be sent to the second terminal, labeled “output terminal.” For this purpose, I will use the “Columnar Transposition” encryption. The link containing detailed information about this encryption method is given below.

The input message will always be in the form of “KEY:ABCD#INPUT_STRING*” where ABCD will be a four character key for the Columnar Transposition, and INPUT_STRING will be 16 character message that will be either encrypted or decrypted.I implemented a button to switch between encryption and decryption modes. The microcontroller will
be in the encryption mode initially, and if the button pressed it will go into decryption mode. Note that, the button can be pressed as many as desired.

MODE             | Input Terminal              | Output Terminal
---------------- | --------------------------- | ---------------------
Encryption Mode  | KEY:DUCK#ITISASAMPLEINPUT*  | IAEUIAPNSMITTSLP
Decryption Mode  | KEY:DUCK#IAEUIAPNSMITTSLP*  | ITISASAMPLEINPUT

Information on Columnar Transposition:
https://en.wikipedia.org/wiki/Transposition_cipher
