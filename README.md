# 🔢 Luhn Algorithm Validator

A simple Python project that validates card numbers using the **Luhn algorithm**, commonly used to verify the validity of credit card numbers, national IDs, and other numeric identifiers.

---

## 🚀 Features

- ✅ Validates numbers using the Luhn algorithm
- 🧮 Works via command-line input
- 🔄 Automatically handles spaces and formatting

---

## 🧠 How the Luhn Algorithm Works

1. Start from the **rightmost digit**.
2. Double every second digit moving left.
3. If the result is >9, **subtract 9**.
4. Sum all the digits.
5. If the total is a multiple of 10, the number is **valid**.

---

## 📦 Installation

Make sure you have **Python 3.x** installed.

Clone the repository:

```bash
git clone https://github.com/longa16/Lunh_Algo.git
cd Lunh_Algo
