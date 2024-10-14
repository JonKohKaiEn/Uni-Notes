# Solving Linear Equations
## Elementary Row Operations (ERO)
3 types of ERO:
1) Interchanging 2 rows ($R_{i} \leftrightarrow R_j$)
2) Multiplying a row by a non-zero constant ($R_{j}\leftarrow \alpha R_{j}, \alpha \neq 0$)
3) Adding a multiple of one row to another ($R_{j} \leftarrow R_{j} + \beta R_i$)
Performing EROs will not change the solution of the linear system
## Definitions
### Row Echelon (RE)
- The leading non-zero term in each non-zero row is a **pivot**
- A matrix is in RE form if all entries in a column below a pivot are zeros
### Reduced Row Echelon (RRE)
- A matrix is in RRE form if
	- Matrix satisfies RE form
	- Each pivot is a 1
	- The pivot is the only non-zero value in its column
## Gaussian Elimination
Converts a matrix to row echelon (RE) form
### Steps
1) Re-arrange rows such that it is easier to do the reduction (preferably with pivot of first row is 1)
2) For each row n, eliminate all values below the pivot of row n
3) Stop when matrix is in RE form
### Cases
- Number of non-zero rows = Number of variables
	- Use back-substitution to solve system
- Number of non-zero rows < Number of variables
	- Multiple solutions
	- Choose one variable to be a free variable, then use back-substitution
- Last row has contradiction
	- No solution
## Gauss-Jordan Elimination
Converts a matrix to reduced row echelon (RRE) form
### Steps
1) Use Gaussian Elimination to convert the matrix to RE form
2) Starting from the bottom row, eliminate all values above the pivot
3) Scale all rows such that all pivots have a value of 1