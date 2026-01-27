Experiment: Operations on Tuples
Student Details
Name: Gayatri Bhosale
PRN: 25070123033
Batch: ENTC A2
Aim
To study the definition, creation, and unique characteristics of Tuples in Python, specifically focusing on their immutability and implementing various built-in operations to solve practical problem statements.

Theory
A Tuple is a built-in data structure in Python used to store collections of data. Unlike Lists, Tuples are immutable, meaning their elements cannot be changed, added, or removed after creation.

Key Characteristics of Tuples:

Immutable: Once created, the items cannot be altered. This is useful for data that should remain constant (e.g., coordinates, fixed configurations).
Ordered: Items have a defined order and are indexed.
Allow Duplicates: Tuples can contain items with the same value.
Heterogeneous: Can store elements of different data types (e.g., ("Maths", 45, "A")).
Experiment: Operations on Tuples
Objectives & Scope
This experiment covers the following operations: Immutability Verification: Demonstrating that item assignment and appending cause TypeError and AttributeError. Concatenation: joining two tuples to create a new one. Slicing: Extracting specific subsets of data. Analysis: Using count() and membership operators (in) for data analysis.

Code Implementation & Problem Statements
The experiment solves the following problem statements:

Verification of Immutability Attempted Modification: Tried changing mytodolist[1] to "repair the laptop". Result: TypeError: 'tuple' object does not support item assignment. Attempted Appending: Tried using .append(). Result: AttributeError: 'tuple' object has no attribute 'append'. Workaround: Demonstrated adding a new tuple (y) to an existing tuple (mytodolist) to create a new combined tuple.

Problem Statement 1: Tuple Slicing Practice Input: A tuple of integers (10, 20, 30, 40, 50). Operations: Printing elements from index 1 to 3. Printing the first 3 elements. Printing elements from index 2 onwards (Reverse Indexing context).

Printing all elements. 3. Problem Statement 2: Student Marks Result Analysis Input: A heterogeneous tuple containing Subject, Marks, and Grade: ("Maths", 45, "A"). Logic: Access elements by index to display Subject, Marks, and Grade. Check if Marks (Index 1) are greater than 75 to determine if "Distinction" is achieved.

Problem Statement 3: Employee Daily Attendance Input: A tuple representing weekly attendance: ("P", "P", "P", "A", "P", "P"). Operations: Count Presence: Used .count("P") to calculate total present days. Count Absence: Used .count("A") to calculate total absent days. Status Check: Used the in operator to check if "A" exists in the tuple to determine if the employee was absent at least once.
How to Run
Ensure Python is installed on your system. Open the tuple operations.ipynb file in Jupyter Notebook or Google Colab. Run the cells sequentially. Note: Some cells will intentionally throw errors (TypeError/AttributeError) to demonstrate the immutable nature of tuples. This is expected behavior.

Conclusion
In this experiment, we successfully explored Python Tuples. We verified their immutable nature by attempting forbidden operations and learned valid manipulation techniques like slicing and concatenation. We also applied tuple methods (count, index) to analyze student performance and employee attendance data.

Objectives & Scope
This experiment covers the following operations: Immutability Verification: Demonstrating that item assignment and appending cause TypeError and AttributeError. Concatenation: joining two tuples to create a new one. Slicing: Extracting specific subsets of data. Analysis: Using count() and membership operators (in) for data analysis.

Code Implementation & Problem Statements
The experiment solves the following problem statements:

Verification of Immutability Attempted Modification: Tried changing mytodolist[1] to "repair the laptop". Result: TypeError: 'tuple' object does not support item assignment. Attempted Appending: Tried using .append(). Result: AttributeError: 'tuple' object has no attribute 'append'. Workaround: Demonstrated adding a new tuple (y) to an existing tuple (mytodolist) to create a new combined tuple.

Problem Statement 1: Tuple Slicing Practice Input: A tuple of integers (10, 20, 30, 40, 50). Operations: Printing elements from index 1 to 3. Printing the first 3 elements. Printing elements from index 2 onwards (Reverse Indexing context). Printing all elements.

Problem Statement 2: Student Marks Result Analysis Input: A heterogeneous tuple containing Subject, Marks, and Grade: ("Maths", 45, "A"). Logic: Access elements by index to display Subject, Marks, and Grade. Check if Marks (Index 1) are greater than 75 to determine if "Distinction" is achieved.

Problem Statement 3: Employee Daily Attendance Input: A tuple representing weekly attendance: ("P", "P", "P", "A", "P", "P"). Operations: Count Presence: Used .count("P") to calculate total present days. Count Absence: Used .count("A") to calculate total absent days.

Status Check: Used the in operator to check if "A" exists in the tuple to determine if the employee was absent at least once.

How to Run
Ensure Python is installed on your system. Open the tuple operations.ipynb file in Jupyter Notebook or Google Colab. Run the cells sequentially. Note: Some cells will intentionally throw errors (TypeError/AttributeError) to demonstrate the immutable nature of tuples. This is expected behavior.

Conclusion
In this experiment, we successfully explored Python Tuples. We verified their immutable nature by attempting forbidden operations and learned valid manipulation techniques like slicing and concatenation. We also applied tuple methods (count, index) to analyze student performance and employee attendance data.
