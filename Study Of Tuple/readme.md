# 🧪 Experiment: Operations on Tuples

## 👩‍🎓 Student Details
- **Name:** Gayatri Bhosale  
- **PRN:** 25070123033  
- **Batch:** ENTC A2  

---

## 🎯 Aim
To study the definition, creation, and unique characteristics of **Tuples** in Python, with special emphasis on their **immutability**, and to implement various built-in tuple operations to solve practical problem statements.

---

## 📘 Theory
A **Tuple** is a built-in data structure in Python used to store collections of data.  
Unlike Lists, **Tuples are immutable**, meaning their elements **cannot be changed, added, or removed** after creation.

### 🔑 Key Characteristics of Tuples
- **Immutable:** Once created, items cannot be altered.  
  👉 Useful for constant data like coordinates or fixed configurations.
- **Ordered:** Items have a defined order and are indexed.
- **Allows Duplicates:** Same values can appear multiple times.
- **Heterogeneous:** Can store different data types  
  *(e.g., `("Maths", 45, "A")`)*

---

## 🛠️ Objectives & Scope
This experiment covers the following tuple operations:
- **Immutability Verification:**  
  Demonstrating that item assignment and appending raise `TypeError` and `AttributeError`.
- **Concatenation:**  
  Joining two tuples to form a new tuple.
- **Slicing:**  
  Extracting specific subsets of tuple data.
- **Analysis:**  
  Using `count()` and membership operators (`in`) for data analysis.

---

## 💻 Code Implementation & Problem Statements
The experiment addresses the following problem statements:

---

### 🚫 Verification of Immutability
- **Attempted Modification:**  
  Tried changing `mytodolist[1]` to `"repair the laptop"`  
  ❌ Result: `TypeError: 'tuple' object does not support item assignment`

- **Attempted Appending:**  
  Tried using `.append()`  
  ❌ Result: `AttributeError: 'tuple' object has no attribute 'append'`

- **Workaround:**  
  Demonstrated concatenating a new tuple (`y`) with an existing tuple (`mytodolist`) to create a **new tuple**.

---

### 🔢 Problem Statement 1: Tuple Slicing Practice
**Input:**  
A tuple of integers `(10, 20, 30, 40, 50)`

**Operations:**
- Print elements from index 1 to 3
- Print the first three elements
- Print elements from index 2 onwards
- Print all elements

---

### 🎓 Problem Statement 2: Student Marks Result Analysis
**Input:**  
A heterogeneous tuple: `("Maths", 45, "A")`

**Logic:**
- Access elements using index positions
- Display Subject, Marks, and Grade
- Check if Marks > 75 to determine **Distinction** 🏆

---

### 🧑‍💼 Problem Statement 3: Employee Daily Attendance
**Input:**  
A tuple representing weekly attendance:  
`("P", "P", "P", "A", "P", "P")`

**Operations:**
- Count present days using `.count("P")`
- Count absent days using `.count("A")`
- Use the `in` operator to check if the employee was absent at least once

---

## ▶️ How to Run
1. Ensure **Python** is installed on your system 🐍
2. Open the `tuple_operations.ipynb` file in:
   - Jupyter Notebook **or**
   - Google Colab
3. Run the cells sequentially ▶️

⚠️ **Note:**  
Some cells will intentionally throw `TypeError` or `AttributeError` to demonstrate tuple immutability.  
This behavior is **expected and correct**.

---

## ✅ Conclusion
In this experiment, we successfully explored **Python Tuples**.  
We verified their **immutable nature** by attempting forbidden operations and learned valid techniques such as **slicing** and **concatenation**.  
Additionally, tuple methods like `count()` and membership operators were applied to analyze **student performance** and **employee attendance** data effectively 📊✨.
