# DataScienceCourse5_Assignment2
**Mastering Advanced Python: Tricky and Situational Programming Challenges — DS PGC Course 5 Assignment 2**

---

## 📘 Assignment Overview
This assignment enhances **problem-solving and Python programming skills** through practical, real-world challenges.  
You’ll work with **strings, tuples, lists, sets, dictionaries, lambda expressions, filters, and modules** to create reusable and optimized code.

---

## 🧩 Tasks Summary
1. Count vowels and consonants in a given string.  
2. Return the minimum and maximum elements from a tuple.  
3. Unpack the first two and remaining elements from a variable-length tuple.  
4. Find the frequency of each word in a sentence.  
5. Detect duplicate elements in a list.  
6. Use a filter with lambda to extract even numbers from a list.  
7. Create a custom module `mymath.py` with `add()`, `sub()`, and `mul()` functions and import it.  
8. Sort a list of tuples by the second element.  
9. Find the symmetric difference between two sets.  
10. Generate all prime numbers up to *n*.

---

## 🧰 Tools & Techniques
- **Language:** Python 3  
- **Editors:** Jupyter Notebook / Google Colab / VS Code  
- **Key Concepts:**  
  - Functions and return values  
  - Lambda expressions and filters  
  - Tuples and sequence unpacking  
  - Dictionaries and `Counter()`  
  - Set operations and symmetric difference  
  - File creation (`mymath.py`) and imports  
  - Prime generation with sieve logic  

---

## 📂 Files Included
- `DataScienceCourse5ProblemStatement.pdf` — assignment brief  
- `DataScienceCourse5SolutionPDFForm.pdf` — formatted solution PDF  
- `DataScienceCourse5SolutionPythonScript.py` — raw Python script  
- `DataScienceCourse5SolutonPythonNotebook.ipynb` — interactive notebook version  

---

## 🧮 Example Code Snippets
```python
# Task 1 – Count vowels and consonants
def count_vowels_consonants(s):
    vowels = set("aeiou")
    v = c = 0
    for ch in s.lower():
        if ch.isalpha():
            if ch in vowels:
                v += 1
            else:
                c += 1
    return v, c

# Task 6 – Filter even numbers
nums = [43, 66, 78, 91, 56]
evens = list(filter(lambda x: x % 2 == 0, nums))
print("Evens:", evens)

# Task 7 – Module example (mymath.py)
def add(a, b): return a + b
def sub(a, b): return a - b
def mul(a, b): return a * b
```

---

## 🧭 How to Review
1. Open the `.ipynb` notebook to view formatted code and outputs.  
2. Open the `.py` script for plain executable code.  
3. Open the PDF for screenshots and explanations.  
4. Optionally, recreate the `mymath.py` module locally and test imports.

---

## 👤 Author
**Utkarsh Anand** — DS PGC Course 5 Assignment 2
