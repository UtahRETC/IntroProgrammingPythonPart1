---
title: Wordle (part 1)
unit: 3
---

In this assignment you will write the first part of a [Wordle](https://www.nytimes.com/games/wordle/index.html) program. Wordle is a popular game where players try to guess a randomly selected five-letter word. Players have six attempts to guess the word. After each attempt, the player is given feedback on how close their guess is. If the word they entered does not match the word they have to guess but it does have a matching letter in the same position, that letter is colored green. If there is a matching letter but in another position, that letter is colored yellow.

Here's [a video that goes over the game's instructions](https://www.youtube.com/watch?v=AQtMRBMw7NM), and here's another one that is just [a demonstration of the game being played](https://www.youtube.com/shorts/Pinnas5Vz4k).

For this assignment, you'll create a program that randomly selects a word for the player to guess, and then gives the player a chance to guess the word. After the player enters their guess, your program should give them feedback on their guess: if they guessed the correct word, you should congratulate them. Otherwise, for each letter in their guess, you should tell them if the letter is in the word and in the correct position, or in the word but not in the correct position, or not in the word at all.

Here are the messages I want you to print to the screen:

- When the guess is correct, print “The word was [the word] and you got it!”
- When the guess was incorrect, for each letter you should print a message:
	- If the letter is in the correct position, print “[the letter]\: great guess”
	- If the letter is in the word but not in the correct position, print “[the letter]\: so close”
	- If the letter is not in the word, print “[the letter]\: bad guess”

For example, when the player guesses the correct word, this is what your end result should look like:

\vspace{.2in}

```text
Enter a word: snake

The word was snake and you got it!
```

\vspace{.2in}

Or when the player guessed an incorrect word:

\pagebreak

```text
Enter a word: lumpy

l: so close
u: great guess
m: bad guess
p: bad guess
y: great guess

The word was bully, better luck next time.
```

\vspace{.2in}

Tips to get you started:

- If the player entered an incorrect word, you'll have to compare each letter of their input for the feedback that you'll give them. You'll need to compare the characters of the word they entered with the characters of the word they were trying to guess.

- To see if the player guessed a letter in the correct position, you'll have to compare the letter found in the two words (the word they had to guess and the word they entered) at the same position (so compare the first letter of the two words, then the second, etc. until you've compared all five letters).

- To compare words, you'll need the equality operator (`==`). This same operator can be used when comparing characters. For example, `"a" == "a"` will return `True`, and `"b" == "c"` will return `False`. Use this to check if the player guessed a word with a letter that is found in the word they had to guess and that letter was found in the same position. This is when you'd tell the player “great guess” because they had the letter right and in the right position.

- To check if a letter is found in a word, you'll need to use the `in` operator. For example `"a" in "snake"` will return `True`, and `"b" in "storm"` will return `False`. Use this to check if the player guessed a word with a letter that is found in the word they had to guess, but the letter was found in a different position. This is when you'd tell the player “so close” because they had the letter right, but not in the right position.

- To access a specific character in a word, you can use the access operator (`[]`). The access operator works with an index, which is zero-based meaning that it starts from 0 instead of 1. For example, to access the first character in a word, you can do `player_input[0]`. To get the third character, you'd do `player_input[2]`.

- You can get a random value from an array using the `choice` function from the `random` module. You can use this to randomly pick a word from a list of words. Refer to the code below for an example.

\vspace{.2in}
\begin{center}
(see next page for code example)
\end{center}
\pagebreak

```python
# We import the 'choice' function from the 'random' module. The 'choice'
# function will be used to randomly pick a value from an array.
from random import choice

# This array holds all of the possible words that we can play Wordle with.
# Later, we will randomly choose a word from this array and that will be
# the word that the player is supposed to guess.
word_options = ["slurp", "video", "right", "rusty", "rhyme",
                "enter", "minty", "nurse", "print", "sandy"]

# Using the 'choice' function, we can how randomly choose a word from the
# array of words stored in the 'word_options' variable. The result is
# then stored in the This is the 'word_to_guess' variable. This is the
# word that the player is supposed to guess.
word_to_guess = choice(word_options)


# Your code starts here
```
