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
