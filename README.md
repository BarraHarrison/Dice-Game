# Dice-Game
This is a simple dice game for 2 to 4 players. The objective of the game is to be the first player to reach or exceed a score of 50 points.


roll() Function:

This function simulates rolling a 6-sided die. It randomly returns a value between 1 and 6.
Player Setup:

The program prompts the user to enter the number of players (between 2 and 4). It ensures the input is valid and within the specified range.
Score Tracking:

The program initializes a list, player_scores, to keep track of each player's total score.
Main Game Loop:

The game loop continues until one of the players reaches or exceeds a total score of 50.
During each player's turn, they can roll the die multiple times. The score for the current turn is accumulated.
If a player rolls a 1, their turn ends immediately, and their score for that turn is reset to 0.
At the end of the turn, if the player has not rolled a 1, the accumulated score is added to their total score.
Ending the Game:

Once a player reaches or exceeds 50 points, the game announces that player as the winner.
