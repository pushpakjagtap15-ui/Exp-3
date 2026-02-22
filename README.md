# #  Experiment 3: Study of Python Lists and Data Handling

## Aim
To study the Python List data structure, explore its mutable properties, and implement basic data analysis operations like indexing, slicing, and statistical functions.

---

## Objectives
- Understand the creation and manipulation of Lists  
- Study various List methods like `append()`, `insert()`, and `extend()`  
- Explore indexing (positive and negative) and list slicing  
- Perform basic statistical analysis (`max`, `min`, `sum`, `average`) on numerical datasets using built-in functions  

---

## Theory

### 1. What is a List?
A **list** is a built-in Python data type used to store a collection of items.  
- **Mutable**: Elements can be changed after creation  
- **Syntax**: `my_list = [1, "hello", 3.5]`

### 2. Key Characteristics
- **Heterogeneous Elements**: Can store integers, strings, booleans, sets, nested lists, etc.  
- **Indexing**:  
  - Zero-based indexing for forward access  
  - Negative indexing for reverse access  
- **Dynamic Sizing**: Lists can grow/shrink using methods like `append()` and `extend()`

### 3. Basic Statistical Functions
- `max(list)` → Largest item  
- `min(list)` → Smallest item  
- `sum(list)` → Total sum  
- `len(list)` → Number of items  
- `sum(list)/len(list)` → Average  

---

## Practical Implementation

###  List Operations

cities = ["Pune", "Mumbai", "Delhi"]
cities.append("Chennai")       # Add at end
cities.insert(1, "Nagpur")     # Insert at index 1
fruits = ["Apple", "Banana"]
fruits.extend(["Mango", "Orange"])  # Extend list
Indexing & Slicinnumbers = [10, 20, 30, 40, 50]
print(numbers[0])     # First element → 10
print(numbers[-1])    # Last element → 50
print(numbers[1:4])   # Slice → [20, 30, 40]
print(numbers[::-1])  # Reverse list → [50, 40, 30, 20, 10]
_ Data Analysis

data = [12, 45, 67, 23, 89]
print("Max:", max(data))       # 89
print("Min:", min(data))       # 12
print("Sum:", sum(data))       # 236
print("Average:", sum(data)/len(data))  # 47.2
Real-world Applications
_ Grocery Shopping List
python
shopping_list = []
shopping_list.append("Milk")
shopping_list.append("Bread")
shopping_list.append("Eggs")

print("Shopping List:")
for item in shopping_list:
    print("-", item)
_ Daily Expense Tracker

expenses = [200, 150, 300, 100, 250, 400, 350]
weekly_total = sum(expenses)
average_expense = weekly_total / len(expenses)

print("Weekly Total:", weekly_total)
print("Average Expense:", average_expense)


Conclusion
In this experiment, the properties and versatility of Python Lists were explored.

Lists can store diverse data types and be modified dynamically

Indexing and slicing allow flexible data access

Built-in statistical functions make lists powerful for analysis

Real-world applications like Expense Tracker and Shopping List demonstrate how lists can manage and analyze datasets effectively
