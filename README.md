# Tic-Tac-Toe with AI

The objective of this project is to create a Tic-Tac-Toe computer game with an Artificial Intelligence opponent.

## Background

Tic-Tac-Toe is a two-player, turn-based game. The actions and win conditions are straightforward and simple to understand. The number of actions in each state is limited, and the state of the game is easily represented.

Two players (each represented by X and O) take turns marking the spaces on a 3x3 grid. The player who succeeds in placing three of their markers in a horizontal, vertical, or diagonal row wins the game.

The possible outcome for a player is a win, loss or draw. A win for one player implies a loss for the other; for this reason, Tic-Tac-Toe is a zero-sum game. 

Each player’s goal state is a win. As such, the player’s goals are competing, which leads us to an adversarial search problem.  

## Motivation

This project allows me to explore AI search algorithms:
* Optimal search
	* Minimax
	* Alpha-Beta Pruning
* Imperfect real-time search
	* Search with cutoff (heuristic evaluation)
 
## Built With

* Python
* Pygame

## Author

**Laura Kocubinski** [laurakoco](https://github.com/laurakoco)

## Acknowledgments

* Boston University MET Master Science Computer Science Program
* MET CS 664 Artificial Intelligence

## References

[1] Russell, Stuart J., and Peter Norvig. Artificial Intelligence: a Modern Approach. Pearson, 2010.
