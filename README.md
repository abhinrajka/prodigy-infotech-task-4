Keylogger with Encryption

Description
This project is a basic keylogger implemented in Python using the pynput library to capture keystrokes and the cryptography library to encrypt the logged data. The keylogger records keystrokes and saves them to an encrypted log file, ensuring that the data is secure.

Features
Logs keystrokes and saves them to a file.
Encrypts the logged data using the cryptography library.
Generates a unique encryption key for each session.
Provides a script to decrypt the log file.


Requirements
Python 3.x
pynput library
cryptography library


Installation
Clone the repository:

git clone https://github.com/abhinrajka/prodigy_infotech_task_4.git
cd prodigy_infotech_task_4


Install the required libraries:

pip install pynput cryptography


Usage
Running the Keylogger
Run the keylogger script:

python keylogger.py
The keylogger will start logging keystrokes and save them to encrypted_key_log.txt. The encryption key will be saved to key.key.

Decrypting the Log File
Run the decryption script:

python decrypt_log.py
The decrypted keystrokes will be saved to decrypted_key_log.txt.

Ethical Considerations
Permission: Always obtain explicit permission from the owner of the device before running a keylogger.
Transparency: Inform users about the keylogger and its purpose.
Legal Compliance: Ensure that your use of the keylogger complies with local laws and regulations.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
pynput
cryptography
