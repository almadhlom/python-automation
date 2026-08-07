# python-automation
⚠️ Auto-generated issue.
If the mentioned files or features do not exist in the repository, please comment first before starting work.
## ✅ Python Tip: Use enumerate() for index and value in loops 

The `enumerate()` function is used when you want both the **index** and
the **value** while looping through a list.

### 🔹 Example:

``` python
fruits = ["apple", "banana", "cherry"]

for index, value in enumerate(fruits):
    print(index, value)
```

### 🔹 Output:

    0 apple
    1 banana
    2 cherry

### ✅ Why use enumerate()?

-   It makes code **clean and readable**
-   You don't need to manually manage a counter
-   Very useful in **automation and data processing**

### 🔹 Tip: Customize the starting index

You can also change the starting index by passing a second argument to `enumerate()`:

``` python
for index, value in enumerate(fruits, start=1):
    print(index, value)
```

This will print indexes starting from 1 instead of 0.

---

## Python Functions

A **function** is a reusable block of code that performs a specific task. Functions help make programs more organized, readable, and reusable.

### Syntax

```python
def greet(name):
    return f"Hello, {name}"

print(greet("Alice"))
```

### Parameters

Parameters are variables defined in the function declaration. They receive values when the function is called.

```python
def add(a, b):
    return a + b

print(add(5, 3))
```

### Return Value

The `return` statement sends a result back to the caller.

```python
def square(num):
    return num * num

print(square(4))
```

Output:

```
16
```

### Variable Scope

Variables created inside a function are **local**, while variables declared outside are **global**.

```python
message = "Global"

def demo():
    local_message = "Local"
    print(local_message)

demo()
print(message)
```

### Why use functions?

- Reuse code instead of repeating it.
- Improve readability.
- Make programs easier to test and maintain.
- Break large problems into smaller tasks.