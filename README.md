# Maze-Search
Program for the navigation of a robot in a maze using UCS and A* algorithms.
This project was done in collaboration with two other fellow students.
Maze: We consider a matrix with NxN cells, some of them are free, while the
others contain obstacles and we can not visit them. Each cell (x,y) is labeled as
free or not by deciding independently with probability p (eg p=0.1).
To each free cell (x,y) we assign a number (called val(x,y)),
which is randomly selected from the integers 1 to 4.
Robot: If robot is in cell (x,y), then it can moves every time 
either horizontally, vertically or diagonally to an neighboring free cell. 
Τhe program finds the path (if any) that the robot should follow starting from one
starting cell (S) to reach the nearest (based on path cost) of two specific
terminal G1 and G2 cells. The (x,y) coordinates of cells S, G1 and G2 are given by the user to
beginning of the program. For each maze, both the UCS method and the A* methodσ are applied.