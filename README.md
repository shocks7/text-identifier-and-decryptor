# Encryption Identifier and Hash Checker

This application helps identify the type of encryption or hash of a given text input. It supports detection of Base32, Base64, Caesar Cipher, and various hashing algorithms.

## Usage

1. **Run the script:**

    Execute the `encryption-identifier.py` script and follow the prompts to input the text you want to identify the encryption or hash for.

    ```bash
    python encryption-identifier.py
    ```

    Follow the on-screen prompts to enter the text. The script will then identify the type of encryption or hash used in the text.

2. **View the results:**

    The script will output the type of encryption or hash detected and, if applicable, additional information such as the decrypted message or the hashing algorithm used.

## Requirements

- Python 3.x
- pycryptodome (for AES encryption and RSA decryption)
- chardet (for encoding detection)
- hashlib (for hashing algorithms)

To install the required dependencies, you can use pip:

```bash
pip install pycryptodome
pip install chardet
pip install hashlib
