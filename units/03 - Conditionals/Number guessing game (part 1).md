---
title: Number guessing game (part 1)
unit: 3
---

For this assignment you will write a number guessing game program. Your program should first generate a random number using the `randint` function from the `random` module as shown in class, then it should print a message to the user asking them to input a number.

Once the user inputs their answer, compare it to the generated number. If the numbers are equal, print a message saying “Correct!”. If the number the user inputted is smaller than the generated number, print a message saying “Too low”. Otherwise, if the number is greater, print a message saying “Too high”.

Before you begin coding, write the pseudocode for this program. Once that's done, start working on the Python code. In order to get full credit for this assignment you must submit both the pseudocode and Python code.

Here's some code to get you started:

\vspace{.2in}

```python
# We import the 'randint' function from the 'random' module. The 'randint'
# function will be used to generated a random number.
from random import randint

# Using the 'randint' function, we can generate a random number that is
# between 1 and 10.
number_to_guess = randint(1, 10)


# Your code starts here.
```
