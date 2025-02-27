# 📝 Text Steganography using AES Encryption

## 🔍 Overview
This project provides a secure way to **hide encrypted messages within text** using **AES encryption** and **zero-width character steganography**. It ensures messages remain invisible while being retrievable by authorized users.

## ✨ Features
- 🔒 **AES-256 Encryption & Decryption** for secure message handling
- 🕵️ **Zero-Width Character Steganography** to embed hidden text
- 👥 **User Authentication System** to restrict access
- 📜 **Seamless Message Extraction** for authorized users

## 📥 Installation
Ensure you have Python installed, then install the required dependencies:

```bash
pip install pycryptodome
```

## 🚀 Usage
### 🔐 Encrypt & Hide a Message
1. Input a **secret message**.
2. Encrypt it using **AES encryption**.
3. Embed the encrypted message within **zero-width characters** inside a cover text.

### 🔍 Extract & Decrypt a Message
1. Retrieve the **hidden message** from the text.
2. Decrypt it using **AES decryption**.
3. Display the **original message** if authentication is successful.


## 📢 Notes
- **Use responsibly!** Steganography should not be used for illegal activities.
- Ensure the **key is kept secure**, as losing it will make decryption impossible.
- The project can be extended to support different encryption methods and larger text embeddings.

