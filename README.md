# NQueen_Python_Challenge

The eight queens puzzle is the problem of placing eight chess queens on an 8×8 chessboard so that no two queens threaten each other; thus, a solution requires that no two queens share the same row, column, or diagonal. The eight queens puzzle is an example of the more general n queens problem of placing n non-attacking queens on an n×n chessboard. (Source : https://en.wikipedia.org/wiki/Eight_queens_puzzle )  
Challenge
The challenge is to generate one right sequence through Genetic Programming. The sequence has to be 8 numbers between 0 to 7. Each number represents the positions the Queens can be placed. Each number refers to the row number in the specific column
0	3	4	5	6	1	2	4

•	0 is the row number in the column 0 where the Queen can be placed
•	3 is the row number in the column 1 where the Queen can be placed

Challenge Submission

1.	The python code should be stored in https://github.com 
2.	The python code should have the following components
a.	Code must follow Object Oriented program standards with appropriate Unit tests
b.	Function to generate the initial population
c.	Function to score the population
d.	Function to do cross over and mutation of the selected gene pool
e.	Main function to identify the right sequence