# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
    The most difficult part was definitely the has_won function. I did the vertical and horizontal checks a little differently, and it helped me finally fully understand the range function and when to use it versus when to use a list. I decided to use the same way that you showed for the diagonals.

2. Explain how you would add a computer player to the game.
    I would add a computer player to the game by removing the change in players, and instead just asking for where either X or O wants to go every time, since the computer will be playing as the other. Specifically what you could do would be add more to the end of the while loop in the play function that would get the turn back to what it was before the iteration of the while loop, so the player can be asked again where to place the symbol that they are playing as.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
    My first idea for how to do this would be just some if statements that react based off of where the player goes. This would work because tic tac toe is a very simple game and I already know how to play it optimally. I could also make it a lot easier and reduce the amount of lines by finding some way to treat certain moves the same way, since technically the only difference between a player going with one side square versus another is that the board is rotated. Another idea I had is that maybe I could run a program that goes through all the possible outcomes of the game, and then saves the ones where the computer wins or doesn't lose, and then searces through the database in some way to find the optimal move in any situation.