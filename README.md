# Tic-Tac-Toe Game with Minimax and Alpha-Beta Pruning

This project implements a **Tic-Tac-Toe** game with two different decision-making algorithms: **Minimax** and **Alpha-Beta Pruning**. The goal of this project is to compare the performance of these two algorithms in terms of game play efficiency and decision-making speed.

## Table of Contents

- [Overview](#overview)
- [Algorithms](#algorithms)
- [Results & Comparison](#results--comparison)

## Overview

The **Tic-Tac-Toe** game is a simple two-player game, where players take turns marking a 3x3 grid with either 'X' or 'O'. The first player to align three of their marks in a row, column, or diagonal wins the game. This project allows the computer to play against a human, using the **Minimax** algorithm and its optimized version, **Alpha-Beta Pruning**, to make decisions.

### Features

- **Two Algorithms**: Minimax and Alpha-Beta Pruning.
- **Game Board**: Interactive 3x3 grid where players can choose a spot for their move.
- **Algorithm Comparison**: Compare the decision-making time and efficiency of the two algorithms.

## Algorithms

### Minimax Algorithm

The **Minimax algorithm** is a recursive method used for decision-making in game theory. It simulates every possible move in the game tree and chooses the optimal move for the player assuming both players play optimally.

### Alpha-Beta Pruning Algorithm

**Alpha-Beta Pruning** is an optimization technique for the Minimax algorithm. It reduces the number of nodes evaluated by the Minimax algorithm by "pruning" branches in the game tree that are unlikely to be selected, improving the efficiency of the algorithm.


## Results & Comparison

In this project, we compare the **Minimax** and **Alpha-Beta Pruning** algorithms based on:

- **Decision-making Speed**: Alpha-Beta Pruning significantly reduces the number of game tree nodes evaluated, leading to faster decisions compared to the standard Minimax algorithm.
- **Performance**: Alpha-Beta Pruning performs better as it prunes branches of the game tree that do not need to be explored, resulting in fewer computations.
  
You can see the results of the performance comparison by analyzing the game log after completing a few rounds with each algorithm.
