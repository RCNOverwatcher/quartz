---
banner: "![[furthermaths.jpg]]"
---
# Matrix Multiplication


> [!Info] Multiplying Matricies
> - **RULE**: In matrix nultiplication, the number of rows of the first matrix have to be the same as the number of columns of the second.
> - **RULE**: Matrix multiplication is non-commutative. This means that the order of multiplying matricies does matter. If you multiply $\mathbf{A}$ by $\mathbf{B}$ then you wont get the same result as $\mathbf{B}$ multiplied by $\mathbf{A}$
> - 3x4 matrix $\times$ 4x2 matrix = 3x2
>
>$\begin{pmatrix}1 &0  & 3 & -2 \\2 & 8 & 4 & 3 \\7 &1  &0  & 2\end{pmatrix}\times\begin{pmatrix}5 & 1 \\1 & 7 \\0 & 3 \\8 & -3\end{pmatrix}=\begin{pmatrix}5+0+0-16 &1+0+9+6  \\10+8+0+24 &2+56+12-9  \\25+1+0+16 & 7-7+0-6\end{pmatrix}=\begin{pmatrix}-11 & 16 \\42 & 61 \\52 &-6 \end{pmatrix}$
>
>- When you multiply by an identity matrix, it doesnt matter what order you multiply in, the result will always be the same.

> [!Example]- $\begin{pmatrix}1 & 2 \\3 & 4\end{pmatrix}\begin{pmatrix}3\\-1\end{pmatrix}$
> $\begin{pmatrix}3-2 & 9-4\end{pmatrix}=\begin{pmatrix}1 & 5\end{pmatrix}$

> [!Example]- $\begin{pmatrix}1 &2  & 3\end{pmatrix}\begin{pmatrix}1 \\2 \\3\end{pmatrix}$
> $\begin{pmatrix}1+4+9\end{pmatrix}$ = $\begin{pmatrix}14\end{pmatrix}$

> [!Example]- $\begin{pmatrix}1 \\2 \\ 3\end{pmatrix}\begin{pmatrix}1 & 2 & 3\end{pmatrix}$
> $$\begin{pmatrix}1 & 2 & 3 \\2 & 4 & 6 \\3 & 6 & 9\end{pmatrix}$$

> [!Info] Rasing matricies to a power
> - You can only raise a matrix to a power if it is a square matrix

> [!Tip] Tip for finding the dimensions of a multiplied matrix
> - If we have two matricies, $\mathbf{A}$ and $\mathbf{B}$
> - To multiply, both $\mathbf{A_{2}}$ and $\mathbf{B_{1}}$ have to be the same.
> - If they are the same, the final multiplied matrix will be of dimensions $\mathbf{A_{1}},\mathbf{B_{2}}$

> [!Example]- $\begin{pmatrix}1 & 3 & 0 \\ 1 & 2 & 1 \\ 3 & 1 & 0\end{pmatrix}\begin{pmatrix}1 & 0 & 1 \\ 2 & 1 & 0 \\ 0 & 0 & 1\end{pmatrix}$
> $$\begin{pmatrix}
7 & 3 & 1 \\ 5 & 2 & 2 \\ 5 & 1 & 3
\end{pmatrix}
