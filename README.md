# GameOfLife

# The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, 
#each of which is in one of two possible states, live or dead. Every cell interacts with its eight neighbours, 
#which are the cells that are directly horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

#1. Any live cell with fewer than two live neighbours dies, as if by loneliness.
#2. Any live cell with more than three live neighbours dies, as if by overcrowding.
#3. Any live cell with two or three live neighbours lives, unchanged, to the next generation.
#4. Any dead cell with exactly three live neighbours comes to life.

# the grid is visualised a matrix of N * N, N = 10. N is not configurable as of now
# state of a cell is 1 - live , 0 - dead

# to the run the program, give in the command prompt

# python game_of_life.py "<seed position>" <number of generation>

# seed position - position of the seed live cells in the format <row1>,<column1>;<row2><coloumn2>...
# number of generation - from the input seed cells, next generation of cells upto the <number of generation> will be generated

# output is shown both as the matrix form, with '1' to indicate the live cells and '0' to indicate dead cells
# the positions of all the live cell for a generations is also displayed
