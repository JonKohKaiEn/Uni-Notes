Linear equations are generally represented in the form
$$
\Large
\begin{cases}
a_{11}x_{1} + a_{12}x_{2} + ... + a_{1n}x_{n} = b_1 \\
a_{21}x_{1} + a_{22}x_{2} + ... + a_{2n}x_{n} = b_2 \\
\quad \vdots \quad + \quad \vdots \qquad \qquad \quad \vdots \quad = \vdots \\
a_{m1}x_{1} + a_{m2}x{2} + ... + a_{mn}x_{n} = b_m \\
\end{cases}
$$
The equations can be represented in the form of an augmented matrix
$$
\Large
\begin{bmatrix}
a_{11} & a_{12} & ... & a_{1n} & \bigm| & b_1 \\ 
a_{21} & a_{22} & ... & a_{2n} & \bigm| & b_2 \\
\vdots & \vdots & \ddots & \vdots & \bigm| & \vdots  \\ 
a_{m1} & a_{m2} & ... & a_{mn} & \bigm| & b_m \\
\end{bmatrix}
$$
Three possible outcomes
- Unique solution
- Many solutions
- No solution
# Elementary Row Operations (ERO)
3 types of ERO
- Interchanging 2 rows ($R_{i} \leftrightarrow R_j$)
- Multiplying a row by a non-zero constant ($R_{j}\leftarrow \alpha R_{j}, \alpha \neq 0$)
- Adding a multiple of one row to another ($R_{j} \leftarrow R_{j} + \beta R_i$)
Performing EROs will not change the solution of the linear system
# Gaussian Elimination
## Steps
0) Re-arrange rows such that it is easier to do the reduction ($x_1$ has a coefficient of 1 in the first row)
1) Use EROs to eliminate $x_1$ in all other rows
2) Repeat step 1 