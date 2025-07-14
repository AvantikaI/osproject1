# 🔐 Parallel File Encryptor

A fast and efficient multithreaded tool to encrypt multiple files in parallel.

This project is designed to demonstrate how parallel processing can speed up encryption tasks by utilizing multiple threads to process files concurrently.

---

## 🚀 Overview

The program reads all files from a given input directory, encrypts them using a symmetric algorithm (AES or XOR), and writes the encrypted output to a separate directory.  
Each file is encrypted on a separate thread to maximize CPU utilization and minimize overall processing time.

---

## ✨ Key Features

- Multithreaded encryption engine
- Batch processing of files from a folder
- Simple command-line interface
- Fast and scalable
- Optionally supports secure AES encryption

---

## 🧠 How It Works

1. User provides input and output folder paths.
2. Program scans the input folder for files.
3. Each file is passed to a separate thread for encryption.
4. Encrypted files are saved to the output folder.

---

## 🛠 Technologies Used

- Language: C++ / Python
- Encryption: AES / XOR
- Threads: C++ std::thread or Python threading module
- I/O: File handling, directory traversal

---

## 📦 Usage Example

### Python:
```bash
pip install pycryptodome
python3 encryptor.py input_folder/ output_folder/
