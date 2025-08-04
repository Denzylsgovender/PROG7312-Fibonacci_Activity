# 🔢 Fibonacci Finder – Recursive vs Iterative Challenge  
## C# GUI Application

---

## 🧠 Overview

In this challenge, you'll build a **C# application** that explores the power (and limits) of **recursion** and **iteration** by computing values from the famous **Fibonacci sequence**.

The Fibonacci sequence is a series where:
- `F(0) = 0`, `F(1) = 1`
- Every next number is the sum of the previous two:  
  `F(n) = F(n-1) + F(n-2)`

> Example:  
> `0, 1, 1, 2, 3, 5, 8, 13, 21...`

---

## 🎯 Learning Objectives

By completing this project, you will:
- Understand **recursive and iterative function design**
- Build a **user interface (UI)** using C# (WinForms or WPF)
- Compare the **performance** of recursion vs iteration
- Gain insight into **algorithm efficiency** and runtime

---

## 🛠️ Your Task

Create a C# GUI application that allows a user to:
1. Enter a number `n`
2. Generate and display the **Fibonacci sequence up to the nth number**
3. Choose between:
   - 🔁 Recursive method
   - 🔄 Iterative method
4. (Optional) Display the **time taken** by each method to compute the sequence

---

## 🖼️ Suggested UI Design

| Element         | Description                                  |
|-----------------|----------------------------------------------|
| TextBox         | For user to input `n`                        |
| Radio Buttons   | Choose between Recursion or Iteration        |
| Button          | `Generate Fibonacci Sequence`                |
| ListBox/TextBox | Display the resulting Fibonacci sequence     |
| Labels (optional) | Show time taken for each method            |

---

## 💻 Sample Recursive Method

```csharp
int FibonacciRecursive(int n)
{
    if (n <= 1) return n;
    return FibonacciRecursive(n - 1) + FibonacciRecursive(n - 2);
}
