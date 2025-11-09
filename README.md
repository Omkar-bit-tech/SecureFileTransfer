# Secure File Transfer System

**Author:** Omkar Ashutosh Kabat  
**Project Type:** Capstone Project (Linux Systems Programming)  
**Repository:** [https://github.com/Omkar-bit-tech/SecureFileTransfer](https://github.com/Omkar-bit-tech/SecureFileTransfer)

---

## 📘 Overview
This project implements a **Secure File Transfer System** using **Socket Programming in C++** for both Linux and Windows environments.  
It allows clients to upload and download files securely to/from a server using a basic XOR-based encryption mechanism for demonstration purposes.

---

## ⚙️ Features
- File upload and download between client and server
- Basic XOR encryption for data transmission
- Cross-platform implementation (Windows & Linux)
- Authentication (username & password)
- Multi-threaded server to handle multiple clients

---

## 🧩 Technologies Used
- **Language:** C++17  
- **Libraries:** POSIX sockets / Winsock2  
- **Build Tools:** Makefile, g++  
- **Optional:** Dockerfile for containerized testing  

---

## 🧪 How to Run
### Linux
```bash
g++ server_linux.cpp -o server -pthread -std=c++17
g++ client_linux.cpp -o client -pthread -std=c++17
./server
./client
