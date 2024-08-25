# Definitions
## Matrix
A matrix is a rectangular array of numbers, e.g.
$$
\Large
A = \begin{bmatrix}
1 & 2 & 3 & 4 \\ 
5 & 6 & 7 & 8 \\ 
9 & 10 & 11 & 12
\end{bmatrix}
$$
- Size of matrix A = $3 \times 4$
- $A_{ij}$ is the i, j element of A

2 matrices are equal if:
- They are the same size
- All corresponding elements are equal
## Vectors
- An $n \times 1$ matrix is considered to be an n-vector
- A $1 \times n$ matrix is called a row vector
- A $1 \times 1$ matrix is considered a number
## Block Matrices
- Block matrices are made with matrices as the entries
- Conditions
	- Matrices in each block row must have the same number of rows
	- Matrices in each block column must have the same number or columns
# Special Matrices
## Zero Matrix
- The zero matrix has all elements as 0, written as $0_{m \times n}$ or just $0$
- Size is inferred when used in block matrices
## Identity Matrix
$$
\large
\begin{bmatrix}
1 & 0 & 0 & 0 \\ 
0 & 1 & 0 & 0 \\ 
0 & 0 & 1 & 0 \\ 
0 & 0 & 0 & 1
\end{bmatrix}
$$
The identity matrix $I$ is:
- A square matrix
- $I_{ii} = 1$
- $I_{ij} = 0$, where $i \neq j$
Size is inferred when used in block matrices
## Diagonal and Triangular Matrices
### Diagonal Matrix
- Square matrix where $A_{ij}=0$, where $i \neq j$
- 