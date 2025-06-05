

---

### 📘 README.md

````markdown
# 🐍 My Python Module – `my_module.py`

Welcome to your custom Python module! This simple yet functional module includes a utility to print student information and a test string for module validation. 📦

---

## 📁 File Contents

### `my_module.py`

```python
print("my_module is imported:")

test_from_mymodule = 'test string'

def student_info(*args, **kwargs):
    print(args)
    print(kwargs)
    return -1
````

---

## 📦 Module Contents

### 🔸 `test_from_mymodule`

📌 A basic string variable to confirm module import.

```python
from my_module import test_from_mymodule

print(test_from_mymodule)  # Output: test string
```

---

### 🔹 `student_info(*args, **kwargs)`

🧑‍🎓 This function accepts any number of positional (`*args`) and keyword (`**kwargs`) arguments, prints them, and returns `-1`.

#### ✅ Example Usage

```python
from my_module import student_info

# Example 1: Only positional arguments
student_info("Alice", "Bob")

# Output:
# ('Alice', 'Bob')
# {}

# Example 2: Only keyword arguments
student_info(name="Charlie", age=22)

# Output:
# ()
# {'name': 'Charlie', 'age': 22}

# Example 3: Mixed arguments
student_info("David", subject="Math", grade="A")

# Output:
# ('David',)
# {'subject': 'Math', 'grade': 'A'}
```

---

## 📙 Usage Guide

You can import this module in any Python script or notebook using:

```python
import my_module
```

Or, for specific components:

```python
from my_module import test_from_mymodule, student_info
```

---

## 🧪 Testing Import

Upon import, the module prints:

```text
my_module is imported:
```

This confirms successful loading. ✅

---

## 🚀 Author

🧠 Created by **Vedant Khopade**
🎓 Exploring Python and modules with creativity and logic!

---

## 📄 License

This module is open for educational and personal use.

```

---

Let me know if you want this turned into a downloadable file or if you'd like to enhance the module (e.g., adding data validation, return summaries, logging, or type annotations).
```
