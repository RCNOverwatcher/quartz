---
banner: "![[furthermaths.jpg]]"
---
# The Inverse of a Linear Transformation

> [!Info] How to undo a linear transformation 


> [!Example]- Exam questions 
> 1. $\mathbf{M=\begin{pmatrix}3 & 4 \\ 2 & -5\end{pmatrix}}$
> $\det \mathbf{M}=-23$
> 
> 2. Given that $\mathbf{A}=\begin{pmatrix}0 & -1 \\ 1 & 0\end{pmatrix}$, describe the linear transformation given by this matrix.
> $\begin{pmatrix}0 & -1 \\ 1 & 0\end{pmatrix}$ = a rotation of 90$^\circ$ anticlockwise.
> 
> 3. Transformation $\mathbf{A}$ followed by transformation $\mathbf{B}$ is equivalent to the transformation $\mathbf{M}$. Find $\mathbf{B}$.
> $\mathbf{AB}=\mathbf{M}$
> $\mathbf{IB}=\mathbf{A^{-1}M}$
> $\mathbf{B}=\mathbf{A^{-1}M}$
> $\mathbf{A^{-1}}=\begin{pmatrix}0 & 1 \\ -1 & 0\end{pmatrix}$
> $\mathbf{B}=\begin{pmatrix}3 & 4 \\ 2 & -5\end{pmatrix}\begin{pmatrix}0 & 1 \\ -1 & 0\end{pmatrix}=\begin{pmatrix}-4 & 3 \\ 5 & 2\end{pmatrix}$

> [!Example]- How many times.... Squashed problem 
> - Applying the matrix $\begin{pmatrix}\frac{1}{2} & 0 \\0 & \frac{1}{2}\end{pmatrix}$ co-ordinates halfs the co-ordiantes.
> - If we apply this matrix to the point $(2, 6)$ on the quadrilateral shown, we get the point $(1, 3)$ which is not inside the circle of radius 3 at the origin.
> - Because this is the co-ordinate with the largest x or y co-ordinate, we can test this to see how many times we should apply the matrix.
> - After applying this matrix twice to this point, we get the point $\left( \frac{1}{2}, \frac{3}{2} \right)$ which is inside the circle at the origin.
> - Therefore we have proved that e only need to apply the matrix twice to get the quadrilateral inside the circle.

