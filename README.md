# Dobble-game-spot-the-similarity

For the basic Spot it! game, reveal one card, then another. Whoever spots the symbol in common on both cards claims the first card, then another card is revealed for players to search, and so on. Whoever has collected the most cards when the 55-card deck runs out wins!

Dobble (also called Spot It!), is a card game that uses special circular cards, each with a number (8 in the standard pack, 6 in the kids pack) of symbols or image. There are various ways to play, but they all the games involve finding which symbol is common to two cards. The cards are designed so that any two cards will always have one symbol in common.

## This got us wondering: how you could design a deck that way?

Three Dobble for kids cards
More formally:

Given n different symbols, how many cards can you make, and how many symbols should be on each card?
Given s symbols per card, how many cards can you make and how many different symbols do you need?
If you want to make k cards, how many symbols do you need on each card, and how many in total?
The requirements for the cards are:

Requirement 1: every card has exactly one symbol in common with every other card.
Requirement 2: each card has the same number of symbols.
Requirement 3: no symbol appears more than once on a given card.

After playing around for a while, I realised that, contrary to my expectation, there's probably no simple formula for the number of symbols and cards. Instead, there is quite a lot of room for exploration. A couple of weeks later, someone asked one of these exact questions on a Facebook group called Actually good math problems (it's a closed group, so you have to join to see the post).

No answer was given on the group, but someone posted links (included at the end of this post) to articles on pairwise balanced design and incidence geometry, so it seems there is real mathematical value in some of these concepts. This article however, is about my more empirical exploration.
