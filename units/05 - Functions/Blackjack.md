---
title: Blackjack (part 1)
---

The first part of this document includes an introduction to the game of
Blackjack, followed by the assignment instructions.

---

Blackjack is a card game where a player is dealt cards while trying to keep the
sum total of the cards under 21. There are two players in Blackjack: the player
and the dealer and they play against each other. Each player is trying to get
to 21, or as close as possible. The player that gets 21 or is closest, wins the
game.

The game starts with two cards dealt to the player and the dealer. At this
point, the player may decide to take another card or to end the game. The
player may continue to take more cards until they reach 21 or go over 21. The
dealer will always take the same action that the player takes, so it's up to
the player to decide when to stop dealing cards.

When the player decides to stop taking cards, each player's cards are added and
the player that comes closer to 21 (or hits 21 exactly) wins the game. You can
play Blackjack online [on this site](https://www.247blackjack.com/).

Face cards (Jack, Queen, and King) are each worth 10, numbered cards (1 through 10) are worth their respective number (2 is worth 2, 5 is worth 5, etc.), and
Aces can be either worth 11 or 1, the player gets to choose which is more
advantageous.

A hand with a 6 of hearts, a 3 of spades, and a 9 of clubs would come to a
total of 18. A hand with an Ace is a little trickier. Let's say you have an 8
of diamonds, a Queen of hearts and an Ace of clubs, this hand could be either
worth 29 (8 + 10 + 11), or 19 (8 + 10 + 1) since the Ace can be either 11 or 1.
In this case, it's better to use the Ace as a 1, otherwise the player would end
with 29 and loose the game.

---

In this assignment you will write the code to generate a legal deck of cards,
shuffle it, deal three cards to each player (the player and the dealer), and
finally calculate the sum total of each card and print whether player or the
dealer won the game.

Cards should be represented by a value (1 - 10, Jack, Queen, King, or Ace) and
a suit (clubs, spades, hearts, diamonds) Shortening Jack, Queen, King, and Ace
to J, Q, K, and A, and clubs, spades, hearts, and diamonds to C, S, H, and D,
you can represent every card in the deck with two letter. For example, 5 of
hearts is represented as 5H, Ace of diamonds is AD, and so on.

The output of your program should be each player's hands and the winner. Your
program's output should match the sample below:

\vspace{.2in}

```
Player: 6C, 9C, 6H, total is 21
Dealer: QS, 5S, 2D, total is 17
Player wins!
```
