# Python for Medical Imaging and Research

## Introduction to Python

### What is Python?
Python is a high-level, interpreted programming language that emphasizes readability and ease of use. It is widely used in research, data science, and medical imaging applications.

### Why Learn Python for Medical Imaging?
- **Simple Syntax**: Easy to learn and use
- **Extensive Libraries**: NumPy, SciPy, Pandas, Matplotlib, OpenCV, SimpleITK, etc.
- **Community Support**: Large research community

### Installing Python
We recommend using Anaconda for scientific computing:
```sh
# Download and install Anaconda from https://www.anaconda.com/
conda create --name miccai_python python=3.9
conda activate miccai_python
```
Alternatively, install Python and Jupyter Notebook manually:
```sh
pip install jupyterlab numpy scipy pandas matplotlib
```

---
## Python Basics

### Variables and Data Types
```python
x = 10         # Integer
y = 3.14       # Float
name = "MICCAI"  # String
is_active = True  # Boolean
```

### Lists and Dictionaries
```python
my_list = [1, 2, 3, 4, 5]
print(my_list[0])  # Accessing elements

my_dict = {"name": "MICCAI", "year": 2025}
print(my_dict["name"])
```

### Conditional Statements
```python
age = 25
if age > 18:
    print("Adult")
else:
    print("Minor")
```

### Loops
```python
for i in range(5):
    print(i)

count = 0
while count < 5:
    print(count)
    count += 1
```

---
## Chapter 3: Functions and Modules

### Defining Functions
```python
def greet(name):
    return f"Hello, {name}!"
print(greet("MICCAI"))
```

### Importing Modules
```python
import math
print(math.sqrt(16))
```

### Creating Your Own Module
Save this as `my_module.py`:
```python
def square(x):
    return x * x
```
Import and use it:
```python
import my_module
print(my_module.square(4))
```

---
## NumPy and Pandas for Data Processing

### NumPy Basics
```python
import numpy as np
array = np.array([1, 2, 3, 4, 5])
print(array * 2)
```

### Pandas Basics
```python
import pandas as pd
data = {"Name": ["Alice", "Bob"], "Age": [25, 30]}
df = pd.DataFrame(data)
print(df)
```

---
## Data Visualization with Matplotlib

```python
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.plot(x, y)
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("Sample Plot")
plt.show()
```

---
## Introduction to Medical Imaging with SimpleITK

```python
import SimpleITK as sitk
image = sitk.ReadImage("sample_image.nii")
sitk.Show(image)
```

---
