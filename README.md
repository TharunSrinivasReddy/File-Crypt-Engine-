# ImageTextEncryptor

A Python-based encryption and decryption tool for both text and images using:

- **Text Encryption**: `cryptography.fernet`
- **Image Encryption**: `AES` (from `pycryptodome`)
- **GUI**: `Tkinter` for user-friendly interface

---

## 🔧 Features

- Encrypt & Decrypt text securely using Fernet
- Encrypt & Decrypt `.jpg`, `.jpeg`, `.png`, `.bmp` images using AES
- Files are securely restored with `_restored` suffix
- GUI-based interaction for encrypting/decrypting image files

---

## 🚀 How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt

