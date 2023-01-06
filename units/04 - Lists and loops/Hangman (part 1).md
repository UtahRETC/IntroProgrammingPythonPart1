---
title: Hangman
---

In this assignment you will write the first part of a [Hangman](https://en.wikipedia.org/wiki/Hangman_(game)) program. Hangman is a word guessing game (like Wordle) where a player tries to guess by guessing a single letter at a time.

Your program should randomly select a word for the player to guess. The program then prints a row of underscores, one for each letter in the word to guess, and then asks the player to enter a letter (this is their guess). Continue to do this until the player correctly guesses all of the letters in the word.

The program should print an underscore as a placeholder for the letter the player is supposed to guess. Continue to print an underscore in place of the letter until the player guesses the letter correctly. Once they guess the correct letter, the letter is "revealed" by printing the letter instead of an underscore in that place. For example, if the word to guess is "enter", you'll first print `_ _ _ _ _`. If the player guesses the letter `e`, print `e _ _ e _`.

When the player guesses all of the letters correctly, your program should print "You win!" and stop.

\vspace{.2in}
\begin{center}
(see next page for an example)
\end{center}
\pagebreak

```text
_ _ _ _ _

Enter a letter: e


e _ _ e _

Enter a letter: n


e n _ e _

Enter a letter: t


e n t e _

Enter a letter: r


e n t e r

You win!
```

\vspace{.2in}

Unlike Wordle, not all words in Hangman are five letters long. Your program should be written in a way where it can handle words of any length and duplicated letters.

Tips to get you started:

- Your program should randomly select a word for the player to guess. Refer to your Wordle program for an example of how to do this.

- It's up to you to decide how to store the guesses a player has made, but using a `list` is going to be your best option. Storing incorrect guesses is not necessary.

- As your program prints the underscores or the correctly guessed letters, include a space after the underscore/letter to make reading it easier. Use `print("_", end=" ")` to print an underscore with a space next to it.

- If the player entered an incorrect word, you'll have to compare each letter of their input for the feedback that you'll give them. You'll need to compare the characters of the word they entered with the characters of the word they were trying to guess.
