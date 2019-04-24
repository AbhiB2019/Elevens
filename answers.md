1.  Deck, Hand, Discard Pile



2. 
Deal enough cards to fill the board(in this case 9).

Check through the cards on the board to see if a play is possible, continue if true, if there are no plays the game restarts.

Player selects the cards they wish to remove.

Make sure the cards that the player selected can be removed legally(add up to 11 or a JQK match). If this is not legal go back to card select.

Remove the selected cards of the board and into some sort of discard pile.

See if there are any cards left in the deck if not you've won so restart the game.

3. No some of it has yet to be implemented.

4. 
a. In the constructor and in the method newGame. 
b. The anotherPlayPossible method, and isLegal 
c. 0, 1, 3, 6, 7 
d. for (int i = 0; i < cIndexes.size(); i++) { 
    System.out.println(cards[cIndexes.get(i)] + "\n"); 
    } 
e. It needs to be called in the anotherPlayPossible function because in the isLegal function it is already handed the selectedCards as a parameter. So it is only in Anpother playPossiblr that it needs to identify what cards are on the board.