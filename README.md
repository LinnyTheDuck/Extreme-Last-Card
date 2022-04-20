# Extreme Last Card

A silly little game I made when I was 12, and now it's a programming project!

## Game Objective
Get rid of your cards. ASAP. (just like regular last card)

## Game Rules

Each player is given the same amount of random cards in their hand, this can be between 5-10 cards. There will be a right-side-up facing card in the middle of the playing table (I'm going to call it the middle card from now on), and to get rid of your cards you have to place matching cards ontop of the middle card. If you cannot place a card, you must pick up an extra card from the remainder of the deck. The players play clockwise from the dealer. <br> The person who gets rid of their cards first is the winner!

### What are Matching Cards?

- Same Number: If the middle card is a `3 of hearts` you can put any card ontop that has the numeric value of `3`
- Same Suit: If the middle card is a `5 of spades` you can put any card ontop that has the suit value of `spades`
- Stacking the Same Number: If the middle card is a `7 of diamonds` and you have the `7 of clubs` and the `7 of spades` you can put both cards down at the same time, the order is up to you
- Ascending/Descending Stacks: If the middle card is a `6 of clubs` and you have the `7 of clubs`, `8 of clubs` and `9 of clubs` you can put all the cards down in ascending order but they all <i>must</i> be of the same suit. You can also double up the middle card numeric value, for example on the `6 of clubs` you can put the `6 of hearts` and `7 of hearts` down in ascending order.
- Jokers and Aces: You can put these on top of any middle card, however you cannot end the game on said card - you <i>must</i> pick up another one from the deck

## Card Values

This is the fun part :) <br> Each card has it's own special abilities. <br>
- Ace/Joker: Change the suit to whichever the player chooses
- 2: <i>Fight Card</i> - If you place this the next player has to pick up two cards for their turn
- 3: <i>Fight Card</i> - Place this shield on a 2 or 5 to prevent yourself from having to pick up cards
- 4: After placing this card the next player gets to discard a card of their choice (this card goes onto the middle pile and overrides all rules)
- 5: <i>Fight Card</i> - If you place this the next player has to pick up five cards for their turn
- 6: <i>Fight Card</i> - Place this undo card on a 3 or 7 to undo the effects of the shield and force the next player to pick up cards
- 7: <i>Fight Card</i> - Place this shield on a 2 or 5 to prevent yourself from having to pick up cards
- 8: The player after you has to take a random card from your hand
- 9: <i>Fight Card</i> - If you place this the next player has to pick up the number of cards instead of you
- 10: The player after you misses a turn. This card is not effective in fight mode.
- 11: The rotation/player order reverses (ie anticlockwise to clockwise)
- 12: Everyone has to show you one of their cards
- 13: The player after you has to do the chicken dance. This doesn't actually affect gameplay and the player still has to place a card afterwards. 12 year old me thought that this was really funny.

### Fight Mode!
You might have noticed all those fight cards. Their special abilities are most useful during the games <i>Fight Mode</i>.

<i>Fight Mode</i> is activated as soon as someone places a card with the numeric value of 2 or 5. During <i>Fight Mode</i>, only <i>Fight Cards</i> of any suit or value can be placed on the previous card. The matching cards rules do not apply in this case. 

The amount of cards that a player must pick up can be increased by having other player place 2's or 5's onto the middle pile. 

The 9 passes on the total cards needed to be picked up onto the next person. These can only be used before blocks (3's and 7's).

`5 -> 9` OR `5 -> 7 -> 6 -> 9`

6's can only be placed after a block.

`5 -> 7 -> 6`

More 2's and 5's can be placed after 6's and/or 9's.

`5 -> 7 -> 6 -> 2` OR `5 -> 9 -> 5`

The fight flow can be stopped with either a 3 or 7 card (unless this is undone by a 6), or once someone picks up the total toll of cards from the deck.

When the game is not in <i>Fight Mode</i> 3, 6, 7 and 9 have no effects.

The first card in the middle has no effect whatsoever.

## Compiling and Running the Software

Hahaha that's on the todo list