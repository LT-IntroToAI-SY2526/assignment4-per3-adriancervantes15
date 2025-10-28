# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
    The most difficult part of this assignment was the has_won function. This is because the result of the function is based on the player given in the parameters. My original code would return true for both players when it should have returned true for one and false for the other. 
2. Explain how you would add a computer player to the game.
    I would add a computer player to the game by first adding another function that asks the user if they want to be 'X" or "O". Next, when it would be the computer's turn I would have a randomizer select a spot that has not been chosen yet. But I think that this would not be a very good bot.
3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
    To get the best move I would have the computer use a strategy from the internet. Like from those videos that tell you how to win every time. But I would change the strategy based on who goes first.