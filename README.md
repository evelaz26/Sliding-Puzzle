## Sliding-Puzzle

The sliding puzzle is a 15-tile game with squares numbered 1-15 arranged in 4x4 grid with one tile missing. Given a board, the goal is to arrange the board such that the tiles are  in ascending order reading left-to-right, top-to-bottom with the blank tile in the last bottom-right space. 

I offer four different search algorithms to find this solution given an initial board. The input should be given in the form of a sequence of numbered tiles for initial board configuration, ‘0’ indicating the empty space. Ex. **1 0 2 4 5 7 3 8 9 6 11 12 13 10 14 15**. Input can be given as a .txt file to read. 

Each solution outputs a string of moves to make with the blank tile to find the goal board where U=Up, L=Left, etc. Also, the number of nodes expanded to find the solution, the time taken to find it, and the total memory used to find it.

Each solution contains **Board.h** & **Board.cpp** that define a Board object and appropriate functions for each algorithm. 
* **BFSTiles.cpp** Breadth-First Search - .
* **IDDFSTiles.cpp** Iterative Deepening Depth-First Search - .
* **Board.cpp** The.
* **Board.cpp** The.
