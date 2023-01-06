---
theme: css/custom-simple.css
highlightTheme: css/layout.css
---

<!-- .slide: class="center" -->

# Introduction to Programming

### Unit 3: Conditionals

---

<!--
paginate: true
footer: 'Unit 2: Variables, values, and user IO'
-->

Making decisions.

---

<span class="centered narrower">

Conditional statements allow your programs to execute parts of its code depending on the values of variables or user input.

</span>

---

"Take your cake out of the oven when it has baked for 35 minutes."

---

"When your cake has baked for 35 minutes, take it cake out of the oven."

---

"If your cake has baked for 35 minutes, take it cake out of the oven."

---

The act of conditionally executing parts of your program is called "branching".

---

Python has different ways to of doing this, but we'll talk about `if` statements today.

---

## `if` statements

<span class="centered narrower">

<pre><code>if <span class="green">condition</span>:
    <span class="blue">code</span>
    <span class="blue">code</span>
</code></pre>

</span>

---

## `if` statements

<span class="centered narrower">

<pre><code>code
code

if <span class="green">condition</span>:
    <span class="blue">code</span>
    <span class="blue">code</span>

code
code
</code></pre>

</span>

---

## Notice the indentation in this code

<span class="centered narrower">

<pre><code>code
code

if <span class="green">condition</span>:
<span class="red">····</span><span class="blue">code</span>
<span class="red">····</span><span class="blue">code</span>

code
code
</code></pre>

</span>

---

## Whitespace in Python

Python cares about when, where, and how many spaces you use in your code.

---

## Whitespace in Python

Python is referred to as being "whitespace sensitive".

---

## Statements and expressions

We're using the word _statement_, but what does it mean?

---

## We can have two branches with `if` and `else`

<span class="centered narrower">

```python
if condition1:
    # code
else:
    # code
```

</span>

---

## We can have many more with `elif`

<span class="centered narrower">

```python
if condition1:
    # code
elif condition2:
    # code
elif condition3:
    # code
elif condition4:
    # code
else:
    # code
```

</span>

---

## Number guessing game

Let's program another game.

---

## Number guessing game

<span class="centered narrower">

For humans, the game is simple: we first think of a number between 1 and 10, and ask our friend to guess the number. If they're correct, we tell them, otherwise we tell them if they guessed too high or too low.

</span>

---

## Number guessing game

<span class="centered narrower">

For computers, the game is similar: our program has to first generate a random number between 1 and 10, then it asks the user to input their guess. If they're correct, it prints a message telling them, otherwise it prints a message tell them if they guessed too high or too low.

</span>

---

## Generating random numbers in Python

<span class="centered narrower">

We first import the `randint` function from the `random` module:

```python
from random import randint
```

<br>

Then we can use `randint` in our program:

```python
randint(1, 10)
```

</span>

---

Let's write the pseudocode for our number guessing program.

---

Let's turn our pseudocode into Python.

---
