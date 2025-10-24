
# 📘 Assignment: Python Basics

## 🎯 Objective

Practice fundamental Python programming skills: user input, string formatting, arithmetic operations, and conditional statements by implementing small, testable functions.

## 📝 Tasks

### 🛠️ User Input and String Formatting

#### Description
Implement a function `welcome_message()` that asks the user for their name, age and favorite color and returns a formatted greeting string.

#### Requirements
Completed program should:

- Ask the user for their name, age and favorite color using `input()`.
- Return a string formatted exactly as:
  `Hello, [name]! You are [age] years old and your favorite color is [color].`
- Include a short example (input → output) demonstrating the function.

Example
```text
Input:
name: Alice
age: 25
color: blue

Output:
Hello, Alice! You are 25 years old and your favorite color is blue.
```

---

### 🛠️ Basic Arithmetic

#### Description
Implement a function `add_two_numbers()` that prompts the user to enter two numbers and prints their sum.

#### Requirements
Completed program should:

- Prompt the user for two numbers (accept integers or decimals).
- Convert inputs to the appropriate numeric type, compute the sum, and print the result.
- Handle incorrect numeric input with a friendly message (optional extra credit).

Example
```text
Enter the first number: 3
Enter the second number: 7
Output: 10
```

---

### 🛠️ Conditional Statements

#### Description
Implement a pure function `is_even(n)` that returns whether an integer is even.

#### Requirements
Completed program should:

- Accept a single integer argument `n`.
- Return `True` if `n` is even, otherwise return `False`.
- Include example usage showing both `True` and `False` results.

Example
```python
def is_even(n):
    return n % 2 == 0

print(is_even(4))  # True
print(is_even(5))  # False
```

---

### Submission notes

- Create a Python file `solutions.py` (or similar) with the three functions above and simple demo code under `if __name__ == "__main__":`.
- Keep examples small and focused so they are easy to run and test.

  print(is_even(5))  # False
  ```

