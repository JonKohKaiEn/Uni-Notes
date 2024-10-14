# Matrix Addition and Scalar Multiplication
## Definitions
Given two $m \times n$ matrices $A$ and $B$,
- $A + B$ means $a_{ij} + b_{ij}$
- $cA$ means $ca_{ij}$
- $A = B$ means $a_{ij} = b_{ij}$
## Properties
![[Pasted image 20240911114956.png]]
# Matrix Multiplication
$(AB)_{ij} = a_{i1}b_{1j} + a_{i2}b_{2j} + ... + a_{in}b_{ni} = \sum\limits_{k=1}^{n}a_{ik}b{kj}$
![[Pasted image 20240911120351.png]]Matrix multiplication is generally not commutative
- if $AB = BA$, we say that $A$ and $B$ **commute**
## Properties
![[Pasted image 20240911120546.png]]
# Transpose
## Definition
$(A^{T})_{ij}= A_{ji}$ 
- Swap the rows and columns
- Converts column vectors to row vectors (and vice versa)
- $(A^{T})^{T}=A$
$$
\Large
\begin{bmatrix}
A & B \\ 
C & D
\end{bmatrix}^T
=
\begin{bmatrix}
A^{T} & C^{T} \\ 
B^{T} & D^{T}
\end{bmatrix}
$$
## Properties
![[Pasted image 20240911121758.png]]