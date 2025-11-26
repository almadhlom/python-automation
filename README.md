# python-automation

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
