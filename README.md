# 🔥 PDF Password Cracker - Python

A fast and efficient PDF password cracking tool built using Python. This script uses a **brute-force attack** with parallel processing to crack password-protected PDF files.

---

## ⚡️ Features
- 🔐 Brute-force attack to unlock password-protected PDF files.
- ⚡️ Parallel processing to speed up password attempts.
- 📚 Supports password combinations with:
  - Lowercase letters (`a-z`)
  - Digits (`0-9`)
- 📄 Automatically saves the unlocked PDF after cracking.

---

## 📚 How It Works
1. Upload a password-protected PDF file.
2. The script generates all possible combinations of passwords using:
   - Lowercase letters (`a-z`)
   - Digits (`0-9`)
3. It tries each password and stops when the correct password is found.
4. The unlocked PDF is saved in the same directory with `_unlocked.pdf` appended to the file name.

---

## 🛠️ Technologies Used
- 🐍 Python 3
- 📚 PyPDF2
- ⚡️ Multiprocessing
- 🧠 Google Colab (Optional)

---

## 🚀 Setup Instructions
### 1. Clone the Repository
```bash
git clone https://github.com/your-username/pdf-password-cracker.git
cd pdf-password-cracker
```

### 2. Install Required Libraries
```bash
pip install -r requirements.txt
```

### 3. Run the Script
```bash
python pdf_password_cracker.py
```

---

### ⚡️ Usage in Google Colab

1. Open [Google Colab](https://colab.research.google.com).
2. Upload the pdf_password_cracker.ipynb file.
3. Run the cells and follow the instructions.
4. Upload your PDF and wait for the password to be cracked.

---

### 🎯 Customization
- You can adjust the maximum password length or character set in the script.
- Modify the max_length or add more character sets like uppercase letters, symbols, etc.

---

### 🛠️ Dependencies
The required dependencies can be installed using:
```bash
pip install -r requirements.txt
```
OR manually install:
```bash
pip install PyPDF2
```

---

### 📄 License
This project is licensed under the MIT License. You are free to modify, distribute, and use this project with attribution.

---

### ❤️ Contributing
Contributions are welcome! 🎉
- If you find a bug or have suggestions, feel free to open an issue or submit a pull request.
---
### 🤝 Acknowledgements
Special thanks to the Python and open-source community for the amazing libraries and tools that make this project possible.

---

### 📬 Contact
- Author: Coder Bhai
- GitHub: [Coder-Bhai](https://github.com/Coder-Bhai)

