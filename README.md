# Computer_Networks


This repository contains practical implementations of core computer networking algorithms, framing techniques, error handling mechanisms, and protocol simulations in C++.

---

## 📌 Repository Overview

This collection covers fundamental concepts in the Data Link, Network, and Transport layers of the OSI model, focusing on low-level bit manipulation, error detection/correction, and socket/protocol logic.

---

## 🛠️ Implemented Programs & Experiments

| No. | Experiment / Topic | Description | File / Source |
| :---: | :--- | :--- | :--- |
| **01** | **Bit Stuffing & Destuffing** | Character/bit-level framing to prevent data pattern misinterpretation. | `bit_stuffing.cpp` |
| **02** | **7-Bit Hamming Code** | Error detection and single-bit error correction using even parity bits. | `hamming_code.cpp` |
| **03** | **Cyclic Redundancy Check (CRC)** | Error detection implementation using polynomial division logic. | `crc.cpp` |
| **04** | **Stop and Wait Protocol** | Elementary flow control protocol simulation across a noisy channel. | `stop_and_wait.cpp` |
| **05** | **IPv4 Class Identifier & Validation** | Inspects IP addresses, identifies their default class (A–E), and validates syntax. | `ip_validator.cpp` |

---

## ⚙️ Prerequisites & Setup

Ensure you have a C++ compiler installed (such as `g++` via GCC or Clang).

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/computer-networks-lab.git](https://github.com/your-username/computer-networks-lab.git)
cd computer-networks-lab
