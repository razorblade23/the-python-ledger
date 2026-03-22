---
id: loops
title: Loops
sidebar_label: 10. Loops
sidebar_position: 11
---

# 🐍 Welcome to the Loop Zone! Python `for` and `while` Loops

Imagine you have to write "I will not throw paper airplanes in class" 100 times on a chalkboard. Doing that by hand sounds exhausting, right? 

In programming, we hate repeating ourselves. When we need the computer to do something over and over again, we don't write the same line of code 100 times. Instead, we use **Loops**. 

Loops are your code's way of saying: *"Keep doing this action until I tell you to stop."*

Today, we are going to master the two main types of loops in Python: the **`while` loop** and the **`for` loop**.

---

## 1. The `while` Loop: The "Keep Going Until..." Loop

A `while` loop runs **as long as a specific condition is True**. 

Think of it like eating pizza. **While** you are still hungry, you will grab another slice. The moment you are full (the condition becomes False), you stop eating.



### The Syntax

```python interactive
hungry = True
slices_eaten = 0

while hungry == True:
    print("Eating a slice of pizza! 🍕")
    slices_eaten += 1
    
    if slices_eaten == 4:
        print("Ugh, I'm stuffed.")
        hungry = False # This stops the loop!
```

### ⚠️ Warning: The Infinite Loop
If you forget to change the condition inside your `while` loop (like forgetting to set `hungry = False`), the computer will run it forever. This is called an **infinite loop**, and it will eventually crash your program! Always make sure your loop has a way to finish.

---

## 2. The `for` Loop: The "Do This For Every Item" Loop

A `for` loop is used when you know **exactly how many times** you want to repeat something, or when you want to go through a sequence of items one by one.

Think of it like checking your grocery list. **For** every item on the list, you find it in the store and put it in your cart. 



### The Syntax (Looping through a List)

```python interactive
grocery_list = ["Apples", "Bananas", "Oatmeal", "Milk"]

for item in grocery_list:
    print("I just put " + item + " in my shopping cart! 🛒")
```

### The `range()` Function
Often, you just want to run a loop a specific number of times. Python gives us a handy tool for this called `range()`.

```python interactive
# This will print numbers 0 through 4
for number in range(5):
    print("Counting: ", number)
```
*Note: Programmers always start counting at 0, not 1! So `range(5)` gives you 0, 1, 2, 3, and 4.*

---

## 🛑 Taking Control: `break` and `continue`

Sometimes you need to interrupt a loop before it naturally finishes. Python gives us two magic words for this:

* **`break`**: Instantly smashes out of the loop completely.
* **`continue`**: Skips the rest of the current loop cycle and jumps right back to the top to start the next cycle.

### Example in Action:
```python interactive
for number in range(10):
    if number == 3:
        continue  # Skips printing 3
    if number == 7:
        break     # Stops the loop entirely when it hits 7
        
    print(number)
```
*(Output: 0, 1, 2, 4, 5, 6)*

---

## 🧠 Quick Recap
* Use a **`while` loop** when you don't know how many times the loop will run, but you know *when* it should stop.
* Use a **`for` loop** when you are going through a collection of items, or you know exactly how many times you want the code to run.

Ready to test your knowledge? Try writing a `for` loop that prints out the letters of your own name, one by one!

```python interactive
my_name = "" # write you name here
```

## Deep dive
https://www.stratascratch.com/blog/python-loops-explained-here-is-how-to-master-them