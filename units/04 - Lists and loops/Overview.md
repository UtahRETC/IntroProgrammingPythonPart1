---
unit: 4
overview: "Introduction to lists and loops. With this complexity comes new creative ways in which we can solve problems with programming."
---

Review the uses of list values. Go over how to break out of a loop and skip an iteration.

Since this is starting to get into the syntax of Python, make sure to point out to students the requirements of indentation and in general the importance of. Go over `while` then `for` loops.

Introduce the `range` function after talking about lists.

- While loop
- For loop
- Lists, append, pop, del, len
- For loop with lists
- Continue / break

### Nested loops example code

```python
row = 0

while row < 5:
	row = row + 1
	column = 0
	while column < 5:
		column = column + 1
		print("x", end="")
	print("")
```

```python
row = 1

while row < 10:
	columns = row
	while columns > 0:
		print("#", end="")
		columns = columns - 1
	print("")
	row = row + 1
```

# Homework

- [[Wordle (part 3)]]
- [[Grid]]
- [[Pyramid]]
- [[Fizz buzz]]
- [[Tic Tac Toe]]
- [[Battleship]]
- [[Hangman (part 1)]]
- [[Dealing Deck]]
- [[Problem set 2]]