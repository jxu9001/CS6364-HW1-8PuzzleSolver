# 8PuzzleSolver
HW1 for CS 6364: Artificial Intelligence

The task is to implement a solver for 8-piece sliding tile puzzles.

How to run:
1. Ensure that the *.py files and the input files are in the same directory.
2. Type "python3 main.py <algorithm_name> <input_file_name>" into the terminal
3. Press enter

algorithm_name is one of:
1. dfs (depth first search)
2. bfs (breadth first search (not required, but useful to calculate the # of moves in the optimal solutions))
3. ids (iterative deepening search)
4. astar1 (a* search with heuristic 1)
5. astar2 (a* search with heuristic 2)

input_file_name is one of:
1. input1.txt (easy, optimal solution has 5 moves)
2. input2.txt (medium, optimal solution has 9 moves)
3. input3.txt (hard, optimal solution has 12 moves)
4. input4.txt (very hard, optimal solution has 30 moves)
