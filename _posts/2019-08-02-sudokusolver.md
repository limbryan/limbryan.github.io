## Sudoku solver 

The solver for a sudoku is often used as a teaching tool or exercise to demonstrate and introduce how search algorithms work. Like most games, Sudoku can be solved by search.

In this case, I used one of the simplest forms of search - DFS (Depth First Search).

## Implementation 
The implementation in code is relatively simple. There is no actual need for any special packaged in numpy. It can be solved with just the use of lists in Python (it is a pretty powerful tool). The bulk of implementation is essentially just for loops and if conditions. 

The most complex or tricky bits of this implementation are:
1. Recursion 
* Recursion is key and is pretty efficient when implementing search algorithms. It is essentially used to go deeper down the tree in the case of depth first search.
2. A way to check the numbers in the big box you are in. 
* The trick here is to identify which of the big boxes you are in using floor division.

The implementation of this in python can be found in the projects section or can be found [here](https://github.com/limbryan)

