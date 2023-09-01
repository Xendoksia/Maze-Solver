# Maze-Solver

The Maze Solver using Breadth-First Search (BFS) is a program written with
Python that uses the BFS algorithm to find the shortest path in a inputted maze.
This algorithm is effective for solving mazes as it finds all possible paths in a
breadth-first manner, guaranteeing that it finds the shortest path from the
starting point to the destination.
The main objective of the program is to take a maze as input and determine the
shortest path from a specified starting point to a specified ending point ,where
the start and ending points are being selected by the user, within the maze.
The maze is represented as a grid of cells, where each cell can either be empty
(input 0) or contain a wall (input 1).
The BFS algorithm is applied to navigate through the maze, considering only
the empty cells(zeros) as valid moves. Thus the program is going to find the
shortest path, where de possible paths are the empty cells (zeros).
The program provides the user to input the maze dimensions, specify the shape
of the maze walls and the path to be drawn, and to select the starting and ending
coordinates.
Once the inputs of the maze has been entered, the program displays the maze as
output to better animate the maze and after all inputs has been entered, it applies
the BFS algorithm to find the shortest path and displays the coordinates of the
path as output.


The top left point is (0,0). 
