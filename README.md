# Sudoku-CSP


## The Problem
Sudoku can be quite a fun game to pass the time. However, the complexity of certain puzzles can stump a human mind for hours. 
Luckily, as usual, computers are incredibly efficient at performing the tasks needed to solve such a puzzle.

## The Solution
The problem of a Sudoku puzzle can be framed as a basic Constraint Satisfaction Problem (CST). 
Using the principles of backtracking and OOP, I created a solution to this CSP in a python Jupyter Notebook. (Description of the algorithm can be found in the Notebook)

## Requirements
* [Python 3.1+](https://www.python.org/)
* [Jupyter Notebook](https://www.python.org/)
* [Numpy](https://www.python.org/)
* [Pandas](https://www.python.org/)
* [Matplotlib](https://www.python.org/)
* [Seaborn](https://www.python.org/)

## Further Study
In addition, I was interested in using this program to discover what made certain puzzles more difficult than others. 
I generated hundreds of random puzzles and then tracked how long it took for each of them to be solved.
By storing information about the puzzle itself and the time needed to solve it I then used Pandas and Seaborn to do some data analysis.
Finally, I created a ML algorithm using this data to predict the difficulty of a puzzle without needing to solve it.

## Acknowledgments
Thank you to these fine gentlemen: [@williamkirschner](https://github.com/williamkirschner) and [@NeilSachdeva](https://github.com/NeilSachdeva), for the help along the way. This project was created for the Pine Crest High School Artificial Intelligence class.
