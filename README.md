# module3
Control Structures in Python

#Task 1: Check if a Number is Even or Odd
Problem Statement:  Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.

This Python script checks whether a given number is **even** or **odd**. Here's a detailed explanation of how it works:

---

### 🔍 **Step-by-step Description:**

1. **Take Input from the User:**

   ```python
   num = input("Enter a number : ")
   ```

   * Prompts the user to enter a number.
   * The input is initially read as a **string**.

2. **Convert Input to Integer:**

   ```python
   num = int(num)
   ```

   * Converts the string input to an **integer** so arithmetic operations can be performed.

3. **Check Even or Odd:**

   ```python
   if(num % 2 == 0):
       print(f"num is an even number.")
   else:
       print(f"num is an odd number.")
   ```

   * Uses the **modulus operator `%`** to check the remainder when `num` is divided by 2:

     * If `num % 2 == 0`, the number is **even**.
     * Otherwise, it is **odd**.
   * Prints the appropriate message.

---

### ✅ **Example Output:**

#### Example 1:

```
Enter a number : 10
num is an even number.
```

#### Example 2:

```
Enter a number : 7
num is an odd number.
```

---

### 🧠 **Key Concepts Used:**

* `input()` for taking user input
* `int()` for type conversion
* `%` modulus operator
* `if-else` conditional statements
* `f-string` formatting for clean output



Task 2: Sum of Integers from 1 to 50 Using a Loop
 
Problem Statement: Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.


This Python script calculates the **sum of all integers from 1 to 50** using a `for` loop. Here's a detailed explanation of how it works:

---

### 🔍 **Step-by-step Description:**

1. **Initialize a Sum Variable:**

   ```python
   sumTotal = 0
   ```

   * A variable named `sumTotal` is initialized to `0`.
   * It will be used to keep a **running total** of the sum.

2. **Loop Through Numbers 1 to 50:**

   ```python
   for num in range(1, 51):
       sumTotal = sumTotal + int(num)
   ```

   * `range(1, 51)` generates numbers from **1 to 50** (note: the end is exclusive, so 51 is not included).
   * In each iteration of the loop:

     * The current number `num` is added to `sumTotal`.
     * `int(num)` is used, though it's actually unnecessary since `num` is already an integer from `range()`.

3. **Print the Final Sum:**

   ```python
   print(f"The sum of numbers from 1 to 50 is : {sumTotal}")
   ```

   * After the loop completes, the total sum is printed using an **f-string**.

---

### ✅ **Expected Output:**

```
The sum of numbers from 1 to 50 is : 1275
```

---

### 🧠 **Key Concepts Used:**

* `for` loop
* `range()` function
* Integer addition and accumulation
* `f-string` for formatted output


