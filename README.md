# NQueen_Python_Challenge - Designed for Python challenge using Genetic computation 

The eight queens puzzle is the problem of placing eight chess queens on an 8×8 chessboard so that no two queens threaten each other; thus, a solution requires that no two queens share the same row, column, or diagonal. The eight queens puzzle is an example of the more general n queens problem of placing n non-attacking queens on an n×n chessboard. (Source : https://en.wikipedia.org/wiki/Eight_queens_puzzle )  
Challenge

The challenge is to generate one right sequence through Genetic Programming. The sequence has to be 8 numbers between 0 to 7. Each number represents the positions the Queens can be placed. Each number refers to the row number in the specific column
0	3	4	5	6	1	2	4

•	0 is the row number in the column 0 where the Queen can be placed
•	3 is the row number in the column 1 where the Queen can be placed

The goal of N-Queens Problem is to place N queens on an N x N chessboard, in a way so that no queen is in conflict with the others.

Challenge Submitted with:
1.	The python code --> NQueen_Python_Challenge.ipnb
2.	The python code have the following components:
      a.	Function to generate the initial population
      b.	Function to score the population
      c.	Function to do cross over and mutation of the selected gene pool
      d.	Main function to identify the right sequence
3. Below are the detailed steps performed:       
      Step a: A random chromosome population is generated via function
      Step b: Fitness score of the chromosome population is computed via function
      Step c: crossover to get a new chromosome from 2 randomly selected best chromosomes computed via function
      Step d: Mutation prosess included
      Step e: New chromosome addition to the population
      step f: Repeation until a chromosome with maximum Fitness value is not found
      

Result validated as per below guideline:
import requests
url='https://lf8q0kx152.execute-api.us-east-2.amazonaws.com/default/computeFitnessScore'
x=requests.post(url,json={"qconfig":"<<config parameters>>","userID":<<emp id>>,"githubLink":"<<git hub link>>"})
print(x.text)

