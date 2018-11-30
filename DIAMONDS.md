# Diamonds  

### Use your spade to dig for diamonds

## Setup:
Diamonds is a 2-3 player card game played with a standard 52 card deck of playing cards, plus two jokers. The cards are ranked Ace-high (ie. 2 is the lowest card, up to 10, J,Q, K, Ace).  

Shuffle the deck and deal the cards face down into 9 equal piles of 6 in a 3x3 grid. Deal a single 3x3 layer of 9 at a time. “Debris” cards, when they appear, are piled face up to one side of the grid.

## Objective:
The objective of the game is to collect a majority of the diamond suit cards by “digging” through each pile. Hearts and clubs are “rocks” equal in hardness to their value. The spade suit are ‘shovels’ used to break hearts and clubs. Each player may only have one spade at a time. The Ace of Spades is the most powerful spade in the game and can break all other rocks.

## Win Condition: 
The player who finds a majority of the diamond suit cards is the winner. The value of the diamond card doesn’t matter, only the number of diamond cards. For 2 players: play to 7 diamonds, 3 players: play to 5 diamonds.

## Gameplay:
The dealer goes first. Given that you are the dealer: 	

* Turn over the top card of one of the 9 piles at random:  
* If the card is a diamond:  
  * Take the diamond, place it in front of you.  
* If the card is a spade:  
  * If you currently have a spade in front of you:  
    * If the card’s value is higher than your current spade you can trade your spade for that one. Your turn is over.  
	* If the card’s value is lower than your current spade you don’t have to take it. Your turn is over.  
  * If you don’t have a spade:  
    * Take the spade, put it in front of you.  
* If the card is a heart or club:  
  * If you don’t have a spade:   
    * You can’t break the rock. Your turn is over.  
  * If you have a spade:  
	* If your spade’s value is equal to or greater than the heart or club, “break” the rock and put  it in the debris pile.  
	* If your spade’s value is less than the heart or club you can’t break it and your turn is over.  
	
If your turn is not over (you were able to clear debris or take a diamond) flip the next card in the current pile and repeat.

## Edge Cases:
Once a pile of six cards is exhausted your turn is over. You cannot switch to a different pile within a single turn.

Unwanted spades are left on the top of piles and cannot be cleared as long as another pile can be dug using your current spade.

If the exposed cards are all upturned spades or unbreakable rocks, you can destroy a weaker spade with your spade and continue digging below as normal. If at this point you hit another spade your turn ends.

If all 9 cards have been turned over and no one can break any of the hearts/clubs, the entire top layer of cards are removed and the game continues as normal.

If a joker is found, take it and place it in front of you. You may continue digging as normal.  
A joker is a one-time use card to steal items from other players. It cannot be used on the turn it is found.  
* Using a joker, you may either:  
  * Steal a diamond from another player (unless stealing a diamond will cause you to win)  
  * Switch spades with another player (even if you don’t have a spade)  
* The joker is then discarded in the debris pile.
