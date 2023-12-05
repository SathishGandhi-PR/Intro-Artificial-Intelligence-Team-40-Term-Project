Tic-Tac-Toe - AI Final project

Project Title - Implementation of Multiple Tic Tac Toe Agents in a Tournament setting

Introduction:

Tic-Tac-Toe is a two-player game which is played in any square grid. Tic-Tac-Toe is a Zero-sum game where the win of player1 is a loss of player2. Usually, it is played by placing either X or O in the grid. If Player1 gets key X, then player2 gets key O. If any player achieves their key in any all the cells of any row or column or diagonal, then that player wins.

Algorithms used:

We have created four Agents to play against each other.

 1. Minimax Agent
 2. AlphaBeta-Minimax Agent
 3. Expectimax Agent
 4. Q-Learning Agent

Minimax Algorithm:

Minimax is a backtracking algorithm which is commonly used in decision making and game theory especially in 2-player zero sum games to make an optimal move. In Minimax tree representation each node will be a game state upon some action performed. It has recursive layers of max and min layers where maximizer tries to maximize the outcome for player and minimizer tries to undermine the outcome of the player.

AlphaBeta Minimax Algorithm:

This is very much like Minimax with the only difference where the algorithm decides which child nodes or other game states the algorithm must check further before returning best value. This is done using alpha and beta values. Alpha holds best value for maximizer and Beta holds best value for minimizer.

Expectimax Algorithm:

This is also like Minimax but other than Minimizer we have chance node which is the average of all available nodes which is the expected utility. This Algorithm does not assume that opponent may always play optimally rather it assumes that their next move is based on chance.

Q-Learning Algorithm:

Q-Learning is reinforcement-based algorithm where initially agent has no idea about the environment. It learns about the environment by playing a few games and getting rewards. By obtaining rewards agents realize which move is good and which is not. This Agent should be trained with the game environment before it can be played with other players in tournament.

Instructions to run code:

 1. Run the file tic-tac-toe using the command python tictactoe.py
 2. Enter agent1 and agent2 as shown in the console and see how the agents play.
3. Run multiple times and check with multiple agents to compare which agent plays the game better.
4. Make sure you select 2 different agents for Tic-Tac-Toe game.


