# Cryptography Ciphers in Python

This repository contains Python implementations of various classical cryptographic ciphers. These ciphers are fundamental in understanding how encryption techniques evolved over time. The following encryption algorithms are included:

## Implemented Ciphers

1. **Caesar Cipher** - A simple substitution cipher that shifts characters by a fixed number of positions in the alphabet.
2. **Monoalphabetic Cipher** - A substitution cipher where each letter in the plaintext is replaced with a corresponding letter from a fixed shuffled alphabet.
3. **Playfair Cipher** - A digraph substitution cipher that encrypts pairs of letters using a 5x5 matrix.
4. **Hill Cipher** - A polygraphic substitution cipher based on matrix multiplication.
5. **Vigenère Cipher** - A polyalphabetic substitution cipher that uses a keyword to determine the shift for each letter in the plaintext.
6. **Feistel Cipher** - A symmetric structure used in many block ciphers , where data is split into halves and repeatedly transformed through a series of rounds.
   

## Prerequisites

Ensure you have Python installed on your system. You can check by running:

```sh
python --version
```

If Python is not installed, download and install it from [python.org](https://www.python.org/downloads/).

## Running the Programs

Each cipher program is a standalone script. Follow these steps to run them:

1. **Clone the repository**

   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Run a specific cipher**

   ```sh
   python caesar_cipher.py
   ```

   ```sh
   python monoalphabetic_cipher.py
   ```

   ```sh
   python playfair_cipher.py
   ```

   ```sh
   python hill_cipher.py
   ```
   ```sh
   python feistel_cipher.py
   ```
   ```sh
   python vignere_cipher.py
   ```
   ```sh
   python helman.py
   ```
   ```sh
   python rsa.py
   ```
   ```sh
   python Des.py
   ```

3. **Follow the on-screen instructions** to encrypt or decrypt messages using the respective ciphers.

## Contributions

Feel free to contribute by submitting issues or pull requests to improve the ciphers or add new features.

