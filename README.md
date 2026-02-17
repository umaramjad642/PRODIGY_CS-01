Caesar Cipher Tool/Program

Prodigy InfoTech - Cybersecurity Internship | Task 01

A professional, Python-based implementation of the Caesar Cipher algorithm. This tool allows for the encryption and decryption of text by shifting characters by a user-defined value.

🚀 Features

* Dual Mode: Supports both Encryption and Decryption within a single interface.

* Continuous Execution: A recursive loop allows users to perform multiple operations without restarting the script.

* Character Integrity: Specifically targets alphabetic characters while maintaining the original formatting of spaces, numbers, and symbols.

* Case Sensitivity: Correctly handles and preserves both uppercase and lowercase letters.

* Error Handling: Built-in validation to prevent crashes from non-integer shift inputs.

🛠️ How It Works

The Caesar Cipher is a type of substitution cipher where each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet.

Mathematical Formula:

* Encryption: $E_n(x) = (x + n) \mod 26

* Decryption: $D_n(x) = (x - n) \mod 26$

📋 Prerequisites

* Python 3.x installed on your system.

* No external libraries are required (uses standard Python libraries).

💻 Usage

Clone the repository or save the script:

```python
git clone https://github.com/your-username/prodigy-cyber-task1.git
cd prodigy-cyber-task1
```

Run the script:

python caesar_cipher.py

Follow the Prompts:

* Enter 'E' to encrypt a message.

* Enter 'D' to decrypt a message.

* Enter 'Q' to safely exit the program.

Input your message and the desired shift key (integer).

🛡️ Security ApplicationIn a SOC (Security Operations Center) environment, understanding basic ciphers like the Caesar Cipher (and its variant ROT13) is crucial for:

* Identifying basic obfuscation used in malicious scripts.

* Analyzing encoded payloads in network traffic.

* Understanding the fundamentals of symmetric key cryptography.
