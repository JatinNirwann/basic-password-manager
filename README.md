# basic-password-manager
 
## Overview

This is a simple command-line password manager implemented in Python. It allows users to securely store and retrieve account credentials using encryption.

## Features

- Add new account credentials
- View stored account credentials
- Encryption of passwords using the Fernet symmetric encryption
- Local storage of encrypted passwords

## Requirements

- Python 3.6+
- cryptography library


## Usage

When you run the script, you'll be presented with a menu:

- To add a new password, type `add` and press Enter.
- To view existing passwords, type `view` and press Enter.
- To quit the program, type `q` and press Enter.

### Adding a Password

1. Choose the `add` option.
2. Enter the account name when prompted.
3. Enter the password when prompted.

### Viewing Passwords

1. Choose the `view` option.
2. The program will display all stored account names and their corresponding decrypted passwords.

## Security Notes

- This is a basic implementation and may not be suitable for storing highly sensitive information without further enhancements.
- The encryption key is stored locally in a file named `key.key`. Ensure this file is kept secure.
- Consider implementing additional security measures such as master password protection for production use.

## File Structure

- `main.py`: The main Python script containing the password manager code.
- `key.key`: Generated file containing the encryption key.
- `passwords.txt`: File where encrypted passwords are stored.

## Contributions

Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.


