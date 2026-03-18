---
id: print-function
title: The Print Function
sidebar_label: 2. The Print Function
sidebar_position: 2
---

# The Print Function: Recording Your First Entry

In the world of **The Python Ledger**, every action needs a record. To "speak" to the outside world, Python uses a built-in tool called a **function**. The most important one for a beginner is the `print()` function.

### What is a Function?
Think of a function as a small machine. You give it some "raw material" (input), it processes it, and it produces a result (output). 

For `print()`, the input is whatever you put inside the parentheses `()`, and the output is that text appearing in your console.



### Strings: The Language of Text
When we want Python to treat something as plain text rather than a command, we wrap it in **quotes**. In programming, a sequence of characters inside quotes is called a **String**.

You can use either single quotes (`'`) or double quotes (`"`), as long as they match:

```python interactive
print("This is a double-quoted string.")
print('This is a single-quoted string.')
```

---

### Special Characters: The New Line
Sometimes you want your Ledger entry to span multiple lines, but you don't want to write ten different `print()` statements. Python uses the **backslash** (`\`) as an "Escape Character" to perform special tricks.

The most common one is `\n`, which stands for **New Line**.

```python interactive
print("Entry Line 1\nEntry Line 2\nEntry Line 3")
```

---

### 🏆 The Ledger Challenge: The Signature
To complete this lesson and verify your "Ledger" is working correctly, you need to sign your work.

**Task:** Use a **single** `print()` function and the `\n` character to print a 3-line signature that looks like this:

```text
NAME: [Your Name]
DATE: 2026-03-18
STATUS: Active
```

:::info

Comments are peaces of text that are ignored by the programming languege, but are useful to us - the developers.

Single line comments in Python start with the character `#`.
Everything after `#` is considered a comment.

:::

**Write your code below:**

```python interactive
# Write your single print statement here!

```

---

## 📚 Deep Dive (Optional)
If you want to see exactly how professional developers use `print()` for debugging, check out these resources:
* [W3Schools: Python Print Function](https://www.w3schools.com/python/ref_func_print.asp)
* [Real Python: Your Guide to the Python print() Function](https://realpython.com/python-print/)

---

## Next Steps
Now that you can output data, it's time to learn how to **store** it.