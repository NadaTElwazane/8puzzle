# 8 Puzzle Solver
This is a simple 8 puzzle solver written in Python. It uses the BFS, DFS, and A* algorithms to solve the puzzle. The A* algorithm can use either the Manhattan distance or the number of misplaced tiles as the heuristic function. The program will output the number of nodes expanded, the maximum number of nodes in memory at any given time, and the solution path. The solution path will be output as a sequence of moves that will take the initial state to the goal state. These moves can be represented as "Up", "Down", "Left", or "Right" in the console, as well as displayed via a GUI. GUI was implemented using Qt.

## Usage
To run the program, simply run the Board_gui.py file, you can change the start state by changing the values in the start_val variable in the BoardWindow Class. 

## Authors
- Haguar Tarek
- Manar Amgad
- Mariem Mostafa
- Nada Elwazane