# Encryption Algorithms in Python

## Overview

This notebook demonstrates the implementation of AES encryption in Python without using predefined libraries for encryption. It includes the implementation of ECB (Electronic Codebook) and CBC (Cipher Block Chaining) modes of operation. Additionally, a small GUI is provided to test the encryption algorithms.

## Contents

1. [Introduction](#introduction)
2. [Implementation](#implementation)
   - [AES Encryption](#aes-encryption)
   - [Padding](#padding)
   - [ECB Encryption](#ecb-encryption)
   - [CBC Encryption](#cbc-encryption)
   - [GUI](#gui)
## Introduction

AES (Advanced Encryption Standard) is a widely used symmetric encryption algorithm. This notebook focuses on implementing AES encryption without relying on predefined libraries. The provided code includes the ECB and CBC modes of operation, along with a graphical user interface (GUI) for testing the encryption algorithms.

## Implementation

### AES Encryption

The notebook contains a Python implementation of the AES encryption algorithm. The encryption is carried out without utilizing predefined encryption libraries.

### Padding

To ensure that the plaintext is a multiple of the given block size, the notebook performs padding using the PKCS7 standard.

### ECB Encryption

The Electronic Codebook (ECB) mode is implemented for AES encryption. ECB is a straightforward mode where each block of plaintext is independently encrypted.

### CBC Encryption

Cipher Block Chaining (CBC) mode is also implemented. This mode involves XORing each plaintext block with the previous ciphertext block before encryption.

### GUI

A small graphical user interface (GUI) is provided for testing the implemented encryption algorithms. The GUI allows users to input plaintext, choose encryption mode, and view the encrypted output.
