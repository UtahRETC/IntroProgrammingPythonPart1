---
unit: 3
overview: "We'll be learning about conditionals which will allow us to write programs that perform different actions depending on a set of conditions that you specify. We'll take this as a chance to review boolean operations."
---

Start with a review of boolean logic and logic operators then move into
conditionals (`if` statements, including `if`, `elif`, and `else`). We're
diving more into the syntax of Python, so talk about whitespace sensitivity.
Also talk about code blocks and how to identify if code "belongs" to an if
statement.

# Homework

- [[Number guessing game (part 1)]]
- [[Stop light simulator]]
- [[Even or odd]]
- [[Discount calculator]]
- [[Wordle (part 1)]]
- [[Rock paper scissors]]

# In class exercises

## Can you get a license?

## Percentage to letter grade

Write a program to ask the user to enter a score then tell them their grade. If
the score is between 100 to 90, print "you have an A". For score between 89 to
80, print "You have a B". For a score between 79 to 70, print "You have a C".
For a score of 70 or lower, print "You have a D".

Example:

```
Please enter a score: 85
You have a B
```

## Budgeting exercise

## Guess the number exercise

Write a program that asks the user to guess the number that is "hardcoded" into
your code. Create a variable to store the number that your program is "thinking
of". Then ask the user to enter their guess. If they guess right, print "You're
correct!". Otherwise, print "Better luck next time".

For extra credit, use the `random.randint` function to generate a number to
guess instead of using a hardcoded solution.

## Guess the number with range check exercise

Write "Guess the number" but first check the user provided a guess that is
between 1 and 10. If it's not, print "That's an invalid guess".

## Login with username and password simulation exercise

Write a program that simulates a user logging into their computer.

First prompt the user for a username. Compare the username provided by the user
with a username of your choice. If the username does not match, print "Unknown
user".

If the username does match, prompt the user for a password. Then compare the
password provided by the user with a password of your choice. If the password
matches, then print "Access granted", otherwise, print "Access denied".

# Movie ticket price exercise

Prompt for an age and a time, then follow the pricing in "Movie ticket price
chart.csv" and show the user the price for a ticket.
