---
unit: 5
overview: "In this unit we'll cover functions. Functions allow us to reuse our code and execute it whenever needed."
---

Functions are units of code that we can reuse by executing them whenever needed. We've already been using functions: `input` and `print` are functions that come with Python. But we can create our own functions as well.

- Using existing functions
- Importing functions from modules
- Defining our own functions
- Returning values
- Passing arguments
- Scope

```python
def show_message():
	print("Hello, world")
```

```python
def show_greeting(name):
	print("Hello " + name + ", welcome to class")
```

```python
def convert_to_inches(feet, inches):
	return feet * 12 + inches

users = [
	["Adam", convert_to_inches(6, 1)],
	["Jenny", convert_to_inches(5, 7)],
]
```

# Homework

- Connect Four
- Tic Tac Toe (part 2)
- [[Blackjack]]
- [[Problem set 3]]