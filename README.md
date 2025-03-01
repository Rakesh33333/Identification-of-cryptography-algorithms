# Identification-of-cryptography-algorithms
# 🔐 Cipher Algorithm Detector

A Python tool that predicts the encryption algorithm used for a given ciphertext based on format, length, and entropy analysis.

## 🚀 Features
- Detects Hex/Base64 encoding.
- Calculates entropy to estimate randomness.
- Predicts AES, DES, 3DES, RC4, RSA, and ECC.
- Provides detailed analysis with entropy score.
  ## Tools & Libraries Used
Python – Core programming language for the script.
Base64 – Used to detect and decode Base64-encoded ciphertexts.
Re (Regex Module) – Helps validate hexadecimal and Base64 formats.
Math – Used for entropy calculation (Shannon entropy formula).
Collections (Counter) – Counts frequency of bytes to compute entropy.
numpy, Pandas, Tensorflow, cryptography...............
