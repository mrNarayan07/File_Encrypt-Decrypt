# File Encryption and Decryption with Python

This repository contains a simple Python script that demonstrates how to encrypt and decrypt files using the `cryptography` library. The script uses the `Fernet` symmetric encryption method, which ensures that your data is encrypted securely.

## Features

- **Generate Key**: Create a new encryption key and save it to a file.
- **Load Key**: Load an existing encryption key from a file.
- **Encrypt File**: Encrypt a specified file using the loaded key.
- **Decrypt File**: Decrypt a specified file using the loaded key.

## Getting Started

### Prerequisites

- Python 3.x
- `cryptography` library

### Installation

1. Install the `cryptography` library if you haven't already:

    ```sh
    pip install cryptography
    ```

2. Clone this repository:

    ```sh
    git clone https://github.com/mrNarayan07/File_Encrypt-Decrypt.git
    ```

3. Navigate to the directory:

    ```sh
    cd File_Encrypt-Decrypt
    ```

## Usage

1. Run the script:

    ```sh
    python file_enc_decr.py
    ```

2. Follow the on-screen prompts to encrypt or decrypt a file.

### Example

To encrypt a file:

    ```sh
    Enter 'E' to encrypt or 'D' to decrypt the file: e
    Enter the file name to encrypt (including file extension): example.txt
    File Encrypted Successfully!!!```


To decrypt a file:

    ```sh
    Enter 'E' to encrypt or 'D' to decrypt the file: d
    Enter the file name to decrypt (including file extension): example.txt
    File Decrypted Successfully!!!```

## Notes

-  Ensure the Secret.key file is kept secure and is not shared with anyone you do not trust, as it is essential for decrypting your files.
-   If the Secret.key file is lost, the encrypted files cannot be decrypted.
