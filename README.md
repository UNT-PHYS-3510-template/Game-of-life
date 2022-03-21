# Game-of-life
Assignment 1: In the life.ipynb file implement a version of Conway's Game of Life using Python classes. The `life` class will represent a game board of dimensions (nx, ny). 
* Implement a constructor for the `life` class, i.e. the `__init__()` method. The constructor should take the two dimensions, `nx` and `ny`, in input and create a rank 2 numpy array of shape `(nx,ny)` with random values of 0 (dead cell) or 1 (living cell).
* Implement the `life.alive()` method to count how many cells are alive in the board.
* Implement the `life.step()` method that evolves the cells of the board according to the standard 3-4 rules: 
    * if a living cell has 2 or 3 neighboring cells that are alive, it stays alive
    * if a dead cell has 3 neighboring cells that are alive, it becomes alive
* Consider several realizations of a 50x50 board with a random initial configuration. Compute and plot the average fraction of living cells as a function of number of steps. 
* (Optional) Create an animation of the game of life.
