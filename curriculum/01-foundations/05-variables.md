---
id: variables
title: Variables
sidebar_label: 5. Variables
sidebar_position: 5
---

# Variables: Labeling the Ledger

In the previous lesson, we printed text directly. But what if you want to use the same piece of information ten times? Or what if that information changes? 

In Python, we use **Variables** to store data. Think of a variable as a **labeled box**. The box holds a value, and the label (the name) allows you to find that value whenever you need it.



### The Assignment Operator
To put something in a box, we use the `=` symbol. In Python, this is called the **Assignment Operator**. 

**Important:** This is NOT the same as "equals" in math. It means "Take the value on the right and store it into the name on the left."

```python interactive
# Assigning a value to a variable
ledger_entry = "Bought 10 apples"

# Using the variable
print(ledger_entry)
```

---

### Reassignment: Updating the Record
The beauty of a variable is that it is *variable* - it can change. If you assign a new value to an existing name, Python throws away the old value and keeps the new one.

```python interactive
current_status = "Level 1: Novice"
print(current_status)

# Now we reassign it
current_status = "Level 2: Apprentice"
print(current_status)
```

---

### Naming Your Variables (The Rules)
You can't just name a variable anything. Python has a few "laws of the land":
1. **No Spaces:** Use underscores instead (`my_variable`).
2. **Start with a Letter:** You cannot start a name with a number (e.g., `1_entry` is illegal).
3. **Be Descriptive:** `x` is a bad name. `user_balance` is a great name.
4. **Case Sensitive:** `Ledger` and `ledger` are two different boxes.

In Python, the community standard is called **snake_case** (all lowercase with underscores).

---

### 🏆 The Ledger Challenge: The Character Sheet
Let's use variables to build a mini "Character Sheet" for your coding journey.

**Task:** 
1. Create a variable called `coder_name` and set it to your name.
2. Create a variable called `coding_level` and set it to `1`.
3. Create a variable called `favorite_language` and set it to `"Python"`.
4. Use a single `print()` statement (or multiple!) to show your stats.

**Write your code below:**

```python interactive
# 1. Define your variables here


# 2. Print them out!

```

---

<details>
  <summary>📚 Deep Dive</summary>

Other resources:
* [Geomar.de: Variables and Assignment](https://2025-pherwiss-2-945e87.pages.geomar.de/content/02_python_basics/02_variables_assignments.html)
* [Real Python: Variables in Python](https://realpython.com/python-variables/)

</details>

## Next Steps
Now that we have boxes to store information, we need to talk about the **different types of stuff** we can put inside them.