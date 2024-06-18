# K-Rail Fence Cipher Encryption/Decryption Algorithm

**Authors:** Leo Martinez III - [LinkedIn](https://www.linkedin.com/in/leo-martinez-iii/)

**Contact:** [leo.martinez@students.tamuk.edu](mailto:leo.martinez@students.tamuk.edu)

**Created:** Spring 2024

---

This Python program implements the K-Rail Fence Cipher, a type of substitution cipher, for encrypting and decrypting messages. The K-Rail Fence Cipher involves creating a zigzag pattern of characters in a matrix with 'rails,' and then reading the characters in a specific order to generate the ciphertext or retrieve the original plaintext.

### Encryption:

- The encryption method fills a matrix in a zigzag pattern based on the key (number of rails) and then extracts the characters to form the ciphertext.
- Spaces are ignored during encryption for better readability.

### Decryption:

- The decryption method reconstructs the zigzag pattern with markers, fills the matrix with characters from the ciphertext, and reads the matrix to obtain the original plaintext.

### Usage:

- The program prompts the user to choose between encryption ('e') or decryption ('d').
- Users enter the key (number of rails), ensuring it is an integer greater than or equal to 2.
- Example values for ciphertext and plaintext are provided for testing purposes.

### Note:

- Program was created in Google Colab with Python 3.9

---

**Folder Contents:**

- **src:** Folder containing the source code python script: `main.py` (use this file to run the program)
- **README.md:** Contains the most basic information about the project
- **LICENSE:** Contains license information in regards to the Github repository

---

**Additional Information:**

- Everything needed along with additional installation information to run the program will be contained in this folder.
