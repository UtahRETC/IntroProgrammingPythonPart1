---
title: Homework 4.1
---


For each of the following fragments of code, write what the output would be. Do
this in your head without running the code (although feel free to check
yourself when you’re done).


1) ```
age = 42
if age > 10:
    print("You may enter")
```
\vspace{0.5in}

1) ```
age = 42
if age > 10:
    print("You may enter")
elif age > 20:
    print("Please try again next year")
```
\vspace{0.5in}

1) ```
age = 42
if age > 20:
    print("Please try again next year")
elif age > 10:
    print("You may enter")
```
\vspace{0.5in}

1) ```
age = 42
if age > 10:
    print("You may enter")
if age > 20:
    print("Please try again next year")
```
\vspace{0.5in}

1) ```
counter = 0
while counter < 3:
    print(counter)
    counter = counter + 1
```
\vspace{0.5in}

1) ```
counter = 0
while counter < 3:
    counter = counter + 1
    print(counter)
```
\vspace{0.5in}

1) ```
counter = 0
while True:
    if counter > 3:
        break
    counter = counter + 1
    print(counter)
```
\vspace{0.5in}

1) ```
counter = 0
while True:
    counter = counter + 1
    if counter > 3:
        break
    print(counter)
```
\vspace{0.5in}

1) ```
counter = 0
while True:
    counter = counter + 1
    print(counter)
    if counter > 3:
        break
```
\vspace{0.5in}

1) ```
friends = ["Alec", "Ryan", "Sean"]
counter = 0
for friend in friends:
    counter = counter + 1
    print(str(counter) + " - " + friend)
```

\newpage

### Examples

The questions below are not part of the assigment, they are examples included
in this document to illustrate how the questions in this assigment should be
answered.


1) ```
print(1 + 3)
```
\vspace{0.25in}
**Question 1 answer:**\
\
4
\vspace{0.5in}

1) ```
logged_in = True
if logged_in:
    print("You may proceed")
else:
    print("Please log in")
```
\vspace{0.25in}
**Question 2 answer:**\
\
You may proceed
\vspace{0.5in}

1) ```
counter = 0
while counter < 3:
    print("counter = " + str(counter))
    counter = counter + 1
```
\vspace{0.25in}
**Question 3 answer:**\
\
counter = 0\
counter = 1\
counter = 2
\vspace{0.5in}
