# 🔢 Fibonacci Activity
## PROG7312 ICE Task

---

## 🧠 Overview

In this activity, you'll explore the magical world of **recursion** by implementing a function to solve the classic **Fibonacci sequence** problem.

The Fibonacci sequence is a famous number series in which:
- The first two numbers are `0` and `1`
- Every number after that is the **sum of the two preceding ones**

> Example:  
> `0, 1, 1, 2, 3, 5, 8, 13, 21...`

Your task is to **use recursion** (no loops!) to calculate the **nth Fibonacci number** and unlock the ancient gates of the legendary city of **Codeonia**. 🔓✨

---

## 🎯 Learning Objectives

By completing this activity, you will:
- Understand and implement **recursive functions**
- Learn how **base cases** and **recursive cases** work
- Apply recursion to solve a classic algorithmic problem
- Recognize recursion’s **limitations and efficiency issues**

---

## 🛠️ Task Instructions

### 1. Write a Recursive Function

Create a C# method that takes an integer `n` and returns the `n`th number in the Fibonacci sequence.

### 🔁 Rules:
- Use recursion (no loops)
- The sequence must start with:
  - `Fibonacci(0) = 0`
  - `Fibonacci(1) = 1`
- For all other values:
  - `Fibonacci(n) = Fibonacci(n - 1) + Fibonacci(n - 2)`

---

## 💻 Sample Output

```csharp
Console.WriteLine(Fibonacci(5));  // Output: 5
Console.WriteLine(Fibonacci(7));  // Output: 13
Console.WriteLine(Fibonacci(10)); // Output: 55
