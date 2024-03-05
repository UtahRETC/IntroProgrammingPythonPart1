---
title: Homework 5.1
---

## Part 1

For each of the following fragments of code in this section, select the block/line of code that the selected statement is a part of.

\vspace{0.2in}

1) What block of code does the statement on line 2 belong to?

    ```{#mycode .python .numberLines}
    if age > 21:
        print("You are old enough")
    ```
\vspace{0.1in}
    a) The global scope.
    a) The `if` statement on line 1.
    a) None of the above.
\vspace{0.4in}

1) What block of code does the statement on line 2 belong to?

    ```{#mycode .python .numberLines}
    while counter < 21:
        if age > 21:
            print("You are old enough")
    ```
\vspace{0.1in}
    a) The global scope.
    a) The `while` statement on line 1.
    a) None of the above.
\vspace{0.4in}

1) What block of code does the statement on line 3 belong to?

    ```{#mycode .python .numberLines}
    while counter < 21:
        if age > 21:
            print("You are old enough")
    ```
\vspace{0.1in}
    a) The global scope.
    a) The `while` statement on line 1.
    a) The `if` statement on line 2.
    a) None of the above.
\newpage

1) What block of code does the statement on line 2 belong to?

    ```{#mycode .python .numberLines}
    def show_message(age):
        if age > 21:
            print("You are old enough")
    ```
\vspace{0.1in}
    a) The global scope.
    a) The `show_message` function on line 1.
    a) None of the above.
\vspace{0.4in}

1) What block of code does the statement on line 5 belong to?

    ```{#mycode .python .numberLines}
    def show_message(age):
        if age > 21:
            print("You are old enough")

    if age > 21:
        print("You are old enough")
    ```
\vspace{0.1in}
    a) The global scope.
    a) The `show_message` function on line 1.
    a) None of the above.

\vspace{1in}
## Part 2

The following questions all relate to the snipped of code below.
\vspace{0.1in}

```{#mycode .python .numberLines}
def search_files(search_text, files):
    found_files = []
    for file in files:
        if search_text in file:
            found_files.append(file)
    return found_files
```

\vspace{0.1in}

6) What block of code does the `return` statement belong to?
\vspace{0.1in}
    a) The global scope.
    a) The `search_files` function on line 1.
    a) The `for` loop on line 3.
    a) The `if` statement on line 4.
    a) None of the above.
\vspace{0.3in}

1) What block of code would the `return` statement belong to if it was indented to the right by one level?
\vspace{0.1in}
    a) The global scope.
    a) The `search_files` function on line 1.
    a) The `for` loop on line 3.
    a) The `if` statement on line 4.
    a) None of the above.
\vspace{0.3in}

1) What block of code would the `return` statement belong to if it was indented to the right by two levels?
\vspace{0.1in}
    a) The global scope.
    a) The `search_files` function on line 1.
    a) The `for` loop on line 3.
    a) The `if` statement on line 4.
    a) None of the above.
\vspace{0.3in}

1) What block of code does the `found_files` declaration on line 2 belong to?
\vspace{0.1in}
    a) The global scope.
    a) The `search_files` function on line 1.
    a) The `for` loop on line 3.
    a) The `if` statement on line 4.
    a) None of the above.
\vspace{0.3in}

1) Using your own words, explain when the `found_files` variable is declared. In other words, when is the variable _created_?
