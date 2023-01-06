---
theme: css/custom-simple.css
highlightTheme: css/layout.css
---

<!-- .slide: class="center" -->

# Introduction to Programming

### Unit 2: Variables, values (and user IO)

---

<!--
paginate: true
footer: 'Unit 2: Variables, values, and user IO'
-->

Programming is about managing and working with "data".

---

"Data" is any information you're dealing with.

---

## Variables

Variables are where you "store" data in your programs.

---

## Values

Values are the data itself.

---

## Mad Lib

Let's learn about variables and values by playing Mad Lib.

---

## Can someone give me:

<span class="centered narrower">

- Two adjectives
- One game
- Three nouns
- One plural noun
- Two verbs ending in "ing"

</span>

---

## Let's play Mad Lib

<span class="centered narrow">

A vacation is when you take a trip to some (<span class="bold underline i">adjective</span>) place with your (<span class="bold underline i">adjective</span>) family. Usually you go to some place that is near a/an (<span class="bold underline i">noun</span>) or up on a/an (<span class="bold underline i">noun</span>). A good vacation place is one where you can ride (<span class="bold underline i">plural noun</span>) or play (<span class="bold underline i">game</span>) or go hunting for (<span class="bold underline i">noun</span>). I like to spend my time (<span class="bold underline i">verb ending in "ing"</span>) or (<span class="bold underline i">verb ending in "ing"</span>).

</span>

---

Before we write the code, let's write the pseudocode.

---

## What is pseudocode?

<span class="centered narrower">

Pseudocode is a made up programming language that helps humans come up with the structure for their code.

</span>

---

## Pseudocode

<span class="centered narrower">

Pseudocode looks like code, but it's intended for humans and not computers.

</span>

---

## Sample pseudocode program

```
if it's 6pm on a Monday or a Thursday
then go to the Python class
```

---

## Sample pseudocode program

```
as long as there is another episode available
then keep watching TV
```

---

<span class="centered narrower">

Pseudocode can look however we want since we make it up, but as we learn more Python our pseudocode will start to look a more like Python.

</span>

---

## Later our pseudocode will start to look more like computer code

```
if it's 6pm on a Monday or a Thursday
then go to the Python class
```

will turn into this:

```
if time equals 6pm and (day equals Monday or Thursday) then
    go to the Python class
```

which will turn into this:

```
if time == 6 and (day == Monday || day == Thursday):
    go_to("Python class")
```

---

Pseudocode code will help us design and write our code.

---

But remember that pseudocode is not code itself.

---

Let's practice.

---

## Mad Lib steps for humans

<span class="centered narrower">

- Ask your friend for:
    - Two adjectives
    - One game
    - Three nouns
    - One plural noun
    - Two verbs ending in "ing"
- Then we add the words into the sentence
- Finally we say the sentence

</span>

---

## Mad Lib steps for computers

<span class="centered narrower">

- We ask the user to enter the needed words:
    - adjective 1, adjective 2
    - game 1
    - noun 1, noun 2, noun 3
    - plural noun 1
    - verb ending in "ing" 1, verb ending in "ing" 2
- Then we add the words into the sentence
- Show the sentence to the user

</span>

---

Let's write the pseudocode code for our Mad Lib program.

---

## Mad Lib pseudocode

```
ask the user for adjective 1.
ask the user for adjective 2.
ask the user for game 1.
ask the user for noun 1.
ask the user for noun 2.
ask the user for noun 3.
ask the user for plural noun 1.
ask the user for verb ending in "ing" 1.
ask the user for verb ending in "ing" 2.

... continues on next slide
```

---

## Mad Lib pseudocode (cont.)

```
... continuation from previous slide

combine "A vacation is when you take a trip to some "
  with adjective 1
  and with " place with your "
  and with adjective 2
  and with " family. Usually you go to some place that is near a/an "
  and with noun 1
  and with " or up on a/an "
  and with noun 2
  and with ". A good vacation place is one where you can ride "
  and with plural noun 1
  and with " or play "
  and with game 1
  and with " or go hunting for "
  and with noun 3
  and with " I like to spend my time "
  and with verb ending in "ing" 1
  and with " or "
  and with verb ending in "ing" 2
  and with "."
  into the final mad lib.

show the final mad lib to the user.
```

---

There's no magic in computer programming.

---

If you didn't code your computer to perform a task, it won't do it.

---

We must specify each step we want the computer to perform in our code.

---

The same applies to our pseudocode.

---

Now let's use words like "input", "output", and "store" in our pseudocode.

---

## Mad Lib pseudocode

```
ask for an adjective and store it in adjective 1.
ask for an adjective and store it in adjective 2.
ask for a game and store it in game 1.
ask for a noun and store it in noun 1.
ask for a noun and store it in noun 2.
ask for a noun and store it in noun 3.
ask for a plural noun and store it in plural noun 1.
ask for a verb ending in "ing" and store it in verb ending in "ing" 1.
ask for a verb ending in "ing" and store it in verb ending in "ing" 2.

... continues on next slide
```

---

## Mad Lib pseudocode (cont.)

```
... continuation from previous slide

combine "A vacation is when you take a trip to some "
  with adjective 1
  and with " place with your "
  and with adjective 2
  and with " family. Usually you go to some place that is near a/an "
  and with noun 1
  and with " or up on a/an "
  and with noun 2
  and with ". A good vacation place is one where you can ride "
  and with plural noun 1
  and with " or play "
  and with game 1
  and with " or go hunting for "
  and with noun 3
  and with " I like to spend my time "
  and with verb ending in "ing" 1
  and with " or "
  and with verb ending in "ing" 2
  and with "."
  and store it in the result.

output the result to the screen.
```

---

Let's turn our pseudocode code into Python

---

## Other types of values

Python has more than just string values.

---

## Other types of values

There are booleans, numbers, lists, dictionaries, tuples, and many others.

---

## Why are the multiple types of values?

Different types of values have different capabilities.

---

## We'll talk about strings, booleans, and numbers today

<span class="centered">

- Strings represent text which can be printed to the screen.
- Integers and floats represent numbers which you can do arithmetic on.
- Booleans represent the answer to yes/no questions.

</span>

---

## Booleans

There are two boolean _values_: `True` and `False`.

---

## Booleans

We'll talk more about booleans when we learn about `if` statements.

---

## Numbers

There are two kinds of numbers in Python: integers and floating point numbers.

---

## Integers

Integers represent whole/natural numbers. For example, `1`, `7`, `42`, `0`, and `-453`

---

## Floats

Floats represent real numbers. For example, `3.14`, `54.654543`, `1.0`, and `-2394.8`

---

## Different capabilities

<span class="centered">

- Strings represent text which can be printed to the screen.
- Integers and floats represent numbers which you can do arithmetic on.
- Booleans represent the answer to yes/no questions.

</span>

---

## Syntax

<span class="centered">

- Strings are surrounded by double-quotes.
- Integers are numbers.
- Integers are numbers with a decimal.
- Booleans are just `True` and `False`.

</span>

---

# Operators

---

## Arithmetic operators

<span class="centered">

<table>
<tr><th>Operator</th><th>Name</th><th>Example</th><th>Result</th></tr>
<tr><td><code>**</code></td><td>Exponentiation</td><td><code>2 ** 3</code></td><td><code>8</code></td></tr>
<tr><td><code>*</code></td><td>Multiplication</td><td><code>43 * 7</code></td><td><code>301</code></td></tr>
<tr><td><code>/</code></td><td>Division</td><td><code>45 / 7</code></td><td><code>6.428571428571429</code>*</td></tr>
<tr><td><code>//</code></td><td>Floor division</td><td><code>45 // 7</code></td><td><code>6</code></td></tr>
<tr><td><code>%</code></td><td>Modulus</td><td><code>45 % 7</code></td><td><code>3</code></td></tr>
<tr><td><code>+</code></td><td>Addition</td><td><code>54 + 543</code></td><td><code>597</code></td></tr>
<tr><td><code>-</code></td><td>Subtraction</td><td><code>654 - 32</code></td><td><code>622</code></td></tr>
</table>

</span>

---

## String operators

<span class="centered">

<table>
<tr><th>Operator</th><th>Name</th><th>Example</th><th>Result</th></tr>
<tr><td><code>+</code></td><td>Concatenation</td><td><code>"abc" + "xyz"</code></td><td><code>"abcxyz"</code></td></tr>
<tr><td><code>*</code></td><td>Multiplication</td><td><code>"ab" * 4</code></td><td><code>"abababab"</code></td></tr>
<tr><td><code>%</code></td><td>Format</td><td><code>"a: %s, b: %s" % ("1", "2")</code></td><td><code>"a: 1, b: 2"</code></td></tr>
</table>

</span>

---

## Comparison operators

<span class="centered">

<table>
<tr><th>Operator</th><th>Name</th><th>Example</th><th>Result</th></tr>
<tr><td><code>==</code></td><td>Equal</td><td><code>7 == 7</code></td><td><code>True</code></td></tr>
<tr><td><code>!=</code></td><td>Not equal</td><td><code>7 != 7</code></td><td><code>False</code></td></tr>
<tr><td><code>></code></td><td>Greater than</td><td><code>43 > 33</code></td><td><code>True</code></td></tr>
<tr><td><code>>=</code></td><td>Greater than or equal to</td><td><code>43 >= 43</code></td><td><code>True</code></td></tr>
<tr><td><code><</code></td><td>Less than</td><td><code>32 < 546</code></td><td><code>True</code></td></tr>
<tr><td><code><=</code></td><td>Less than or equal to</td><td><code>32 <= 31</code></td><td><code>False</code></td></tr>
</table>

</span>

---

## Boolean operators

<span class="centered">

<table>
<tr><th>Operator</th><th>Example</th><th>Result</th></tr>
<tr><td rowspan="3"><code>and</code></td><td><code>True and True</code></td><td><code>True</code></td></tr>
<tr><td><code>True and False</code></td><td><code>False</code></td></tr>
<tr><td><code>False and False</code></td><td><code>False</code></td></tr>
<tr><td rowspan="3"><code>or</code></td><td><code>True or True</code></td><td><code>True</code></td></tr>
<tr><td><code>True or False</code></td><td><code>True</code></td></tr>
<tr><td><code>False or False</code></td><td><code>False</code></td></tr>
<tr><td rowspan="2"><code>not</code></td><td><code>not True</code></td><td><code>False</code></td></tr>
<tr><td><code>not False</code></td><td><code>True</code></td></tr>
</table>

</span>

---

## Complex boolean expressions

<span class="centered">

- `(2 < 43 or 453 >= 23 or 3 > 1) and (43 > 65)`
- `34 <= (3 + 34) and not (43 < 2 or 3 != 3)`
- `True and not False or False`
- `True and not True or True`
- `True and not (True or True)`

</span>

---

# Casting

---

## Casting

Casting is the act of converting a value of one type to another type.

---

## Casting

If you have a string but you need to use it as an integer, you have to cast it.

---

## Casting

<span class="centered">

- `str` casts a value to a string
- `int` casts a value to an integer
- `float` casts a value to a float

</span>

---

# Problem set

---
