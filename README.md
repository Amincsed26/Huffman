# 🧩 Huffman Coding Project

## 📌 Overview

This project implements the **Huffman Coding algorithm**, a widely used technique for **lossless data compression**.

The program builds a Huffman tree based on character frequencies and generates optimal binary codes to reduce the total size of data. This technique assigns shorter codes to frequent characters and longer codes to less frequent ones ([GitHub][1]).

---

## 🖼️ Project Preview

![image](https://github.com/user-attachments/assets/c05e3624-4a64-4481-b626-0951eacb89ea)

---

## 🎯 Features

* Builds Huffman Tree using character frequencies
* Generates binary codes for each character
* Encodes input data efficiently
* Decodes compressed data back to original
* Demonstrates lossless compression

---

## 🧠 Concepts Used

* Data Structures (Trees, Priority Queue / Min-Heap)
* Greedy Algorithms
* File Handling (if implemented)
* Bit manipulation

---

## ⚙️ How It Works

### 1. Frequency Calculation

* Count how many times each character appears in the input

### 2. Build Huffman Tree

* Use a priority queue (min-heap)
* Merge nodes with the smallest frequencies repeatedly

### 3. Generate Codes

* Traverse the tree:

  * Left → 0
  * Right → 1

### 4. Encoding

* Replace each character with its Huffman code

### 5. Decoding

* Use the Huffman tree to reconstruct the original data

---

## ▶️ Compilation & Execution

Compile:
gcc huffman.c -o huffman

Run:
./huffman

---

## 🧪 Example

Input:
hello

Possible Output:
Encoded: 101010...
Decoded: hello

(Note: actual codes depend on frequency distribution)

---

## 🚨 Advantages

* Reduces file size without losing data
* Efficient for text compression
* Widely used in real-world compression algorithms
