# Huffman-compression-Algorithm

# 📦✨ Huffman Coding - File Compression & Decompression 🚀

![Huffman Tree](https://img.shields.io/badge/Data%20Structures-Huffman%20Coding-blue?style=for-the-badge)
![C++](https://img.shields.io/badge/Language-C++-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

---

## 🌟 Project Overview

Welcome to **Huffman Coding - File Compression & Decompression Tool** 🎉
This project demonstrates the powerful concept of **Huffman Coding**, a greedy algorithm for **lossless data compression** 📉➡️📈.

With this project, you can **encode (compress)** and **decode (decompress)** text files using Huffman’s algorithm ⚡. The goal is to minimize file size while ensuring **no data is lost**! 🔐

---

## 📂 File Structure

```
📦 Huffman-Coding
 ┣ 📜 decode.cpp      # 💡 Logic for decompressing files
 ┣ 📜 encode.cpp      # ⚡ Logic for compressing files
 ┣ 📜 huffman.cpp     # 🧠 Implementation of Huffman Tree & algorithm
 ┣ 📜 huffman.hpp     # 📘 Header file containing function & class declarations
 ┣ 📜 inputFile.txt   # 📝 Sample input file to test compression
```

---

## ⚙️ How It Works

1. **Build Frequency Table** 📊 → Count frequency of each character.
2. **Construct Huffman Tree** 🌳 → Greedy approach using min-heap.
3. **Generate Huffman Codes** 🔢 → Shorter codes for frequent chars.
4. **Encode File** 📦 → Replace characters with Huffman codes.
5. **Decode File** 🔓 → Rebuild original text from encoded bits.

---

## 🚀 Getting Started

### 🔧 Compilation

```bash
# Compile the project
$ g++ encode.cpp huffman.cpp -o encode
$ g++ decode.cpp huffman.cpp -o decode
```

### ▶️ Usage

```bash
# To compress a file
$ ./encode inputFile.txt compressed.bin

# To decompress a file
$ ./decode compressed.bin outputFile.txt
```

---

## 🎯 Features

✨ **Lossless Compression** → 100% original data recovery
✨ **Greedy Algorithm** → Optimal encoding using frequencies
✨ **Modular Code** → Clean separation of logic in `.cpp` and `.hpp` files
✨ **Scalable** → Works on large files (tested on MB-level data) ⚡

---

## 📸 Screenshots

📥 **Input File**
A text file of size `2.2 MB` 📝

📤 **Compressed File**
Size significantly reduced ⚡📉

📂 **Decompressed File**
Exactly matches the original ✅

---

## 🧑‍💻 Author

👨‍🎓 **Ridham Garg**
🎓 Thapar Institute of Engineering and Technology, Patiala
🌟 Passionate about Data Structures, Algorithms & Real-World Applications 🚀

---

## 💡 Future Enhancements

* 🌐 Add GUI for easier interaction.
* 📊 Show real-time compression statistics.
* 🗜️ Support for binary/image files.

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub! 🌟
Let’s make file compression fun & efficient together 💻✨

---

🔥 *Data Compression Made Simple with Huffman Coding!* 🔥
