# 🧮 Simple Multi-Number Calculator in C

A basic **command-line calculator** written in C that performs arithmetic operations on multiple numbers.  
It supports **addition, subtraction, multiplication, and division** for up to **10 numbers** entered by the user.

---

## 🚀 Features

- Perform operations on **multiple numbers** (not just two)
- Supported operators:
  - `+` → Sum of all numbers  
  - `-` → Subtracts all numbers sequentially  
  - `*` → Product of all numbers  
  - `/` → Divides the result sequentially by each number  
- Simple, user-friendly console interface  

---

## 🧠 How It Works

1. The program asks how many numbers you want to calculate.
2. You enter all the numbers.
3. You choose an operator (`+`, `-`, `*`, `/`).
4. The corresponding function is called:
   - `sumofnumbers()` → for addition  
   - `diffofnumbers()` → for subtraction  
   - `productofnumbers()` → for multiplication  
   - `divofnumbers()` → for division  
5. The final result is displayed.

---

## 💻 Example Usage

    Calculator
How many Numbers : 4
Enter 4 numbers : 5 10 15 20
enter operator : +
Sum of number : 50.000000
