---
banner: "![[furthermaths.jpg]]"
---
# Inverting a 3x3 Matrix

> [!Info] Inverting a 3x3 matrix
>> - Firstly, find the determinant of your matrix.
> 
>> - Second, you form a matrix of minors
>> - To do this, you find the minor of each value in the matrix and overwrite the original value in your result in a new matrix.
>
>> - Next, you form a matrix of co-factors.
>> - A cofactor is just a *signed minor*.
> >- This means we put in pluses and minuses in a pattern.
> >- $\begin{pmatrix}+ & - \\ - & +\end{pmatrix}$
>
>>- Finally, you find $\frac{1}{\text{det of the ORIGINAL matrix}}$ and times it by a transposed version of your co-factor matrix.
>>- This gives $\mathbf{A^{-1}}$ for any matrix.

> [!Example]- Applying this to a 2x2 matrix to start
> - $\mathbf{B}=\begin{pmatrix}2 & -3 \\ 1 & -5\end{pmatrix}$
> - $\det \mathbf{B}=-10+3=-7$
> - $\mathbf{M}=\begin{pmatrix}-5 & 1 \\ -3 & 2\end{pmatrix}$
> - $\mathbf{C}=\begin{pmatrix}-5 & -1 \\ 3 & -2\end{pmatrix}$
> - $\mathbf{C^T}=\begin{pmatrix}-5 & 3 \\ -1 & 2\end{pmatrix}$
> - $\mathbf{B^{-1}}=-\frac{1}{7}\begin{pmatrix}-5 & 3 \\ -1 & 2\end{pmatrix}$

> [!Example]- Applying this to a 3x3 matrix
> 	- $\mathbf{A}=\begin{pmatrix}1 & 3 & 1 \\ 0 & 4 & 1 \\ 2 & -1 & 0\end{pmatrix}$
> 	- $\det \mathbf{A}=(1\times1)-(3\times -2)+(1\times -8)=1+6-8=-1$
> 	- $\mathbf{M}=\begin{pmatrix}1 & -2 & -8 \\  1 & -2 & -7 \\ -1 & 1 & 4\end{pmatrix}$
> 	- $\mathbf{C}=\begin{pmatrix}1 & 2 & -8 \\ -1 & -2 & 7 \\ -1 & -1 & 4\end{pmatrix}$
> 	- $\mathbf{C^T}=\begin{pmatrix}1 & -1 & -1 \\ 2 & -2 & -1 \\ -8 & 7 & 4\end{pmatrix}$
> 	- $\mathbf{A^{-1}}=-1\begin{pmatrix}1 & -1 & -1 \\ 2 & -2 & -1 \\ -8 & 7 & 4\end{pmatrix}=\begin{pmatrix}-1 & 1 & 1 \\ -2 & 2 & 1 \\ 8 & -7 & -4\end{pmatrix}$