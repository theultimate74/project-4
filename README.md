# 🔐 AES-256 File Encryptor & Decryptor

A **Python-based encryption tool** to securely **encrypt and decrypt files using AES-256 (CBC mode)**. Designed with security best practices, a simple interface, and no external dependencies beyond PyCryptodome.

---

## ⚙️ Features

- 🔐 AES-256 encryption using CBC mode
- 🧂 Salted key derivation with PBKDF2 (1,000,000 iterations)
- 🔁 Automatic IV generation and secure storage
- 🛡️ Password-protected encryption
- ✅ Simple CLI interface for encryption/decryption
- 🔒 Padding support to handle any file type

---

## 🚀 Getting Started

### 📦 Requirements

- Python 3.6+
- [`pycryptodome`](https://pypi.org/project/pycryptodome/)

Install using pip:

```bash
pip install pycryptodome
