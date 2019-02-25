# Tic-Tac-Toe with AI

A Tic-Tac-Toe GUI application with an AI opponent.

## Background

Tic-Tac-Toe is a two-player, turn-based game. The actions and win conditions are straightforward and simple to understand. The number of actions in each state is limited, and the state of the game is easily represented.

Two players (each represented by *X* and *O*) take turns marking the spaces on a 3x3 grid. The player who succeeds in placing three of their markers in a horizontal, vertical, or diagonal row wins the game [1].

The possible outcome for a player is a win, loss or draw. A win for one player implies a loss for the other; for this reason, Tic-Tac-Toe is a zero-sum game. 

Each player's goal state is a win. As such, the player's goals are competing, which leads us to an adversarial search problem.  

## Motivation

This project explores tradeoffs between AI search algorithms:
* Optimal decisions
	* Minimax
	* Alpha-beta pruning
* Imperfect real-time decisions
	* Alpha-beta with cutoff (heuristic evaluation)
 
## Built With

* Python 2.7
* [Pygame](https://www.pygame.org/)

## Usage

```python
python run_tic_tac_toe.py
```

This will launch a pygame window.

<img src="images/Board_1.png" height="400"> <img src="images/Board_2.png" height="400">

The terminal will prompt the choice of AI:

1. Random
2. Minimax
3. Alpha-beta
4. Alpha-beta with cutoff

## Author

**Laura Kocubinski** [laurakoco](https://github.com/laurakoco)

## Acknowledgments

* Boston University MET Master Science Computer Science Program
* MET CS 664 Artificial Intelligence

## References

[1] [https://en.wikipedia.org/wiki/Tic-tac-toe](https://en.wikipedia.org/wiki/Tic-tac-toe)

[2] Russell, Stuart J., and Peter Norvig. Artificial Intelligence: a Modern Approach. Pearson, 2010.
