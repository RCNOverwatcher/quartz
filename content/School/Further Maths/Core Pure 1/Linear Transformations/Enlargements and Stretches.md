---
banner: "![[furthermaths.jpg]]"
---
# Enlargements and Stretches

> [!Info] Enlargements 
> - $\begin{pmatrix}a & 0 \\ 0 & b\end{pmatrix}$ represents a stretch of scale factor **$a$** parallel to the x-axis and a stretch of scale factor **$b$** that is parallel to the y-axis.
> - When $a=b$, this is an enlargement.

> [!Example]- Stretch of factor 2 in the x axis
> $$\begin{pmatrix}2 & 0 \\ 0  & 1\end{pmatrix}$$

> [!Example]- Stretch of factor 4 in the x direction and stretch of factor 16 in the y direction
> $$\begin{pmatrix}4 & 0 \\0 & 16\end{pmatrix}$$

> [!Example]- Using the derivative to calculate areas
> $A(1, 1), B(1, 2), C(2, 2)$ are points on a triangle. The transformation of matrix $\mathbf{M}=\begin{pmatrix}4 & 0 \\ 0 & 3\end{pmatrix}$ is applied to the triangle.
> 1. New coords are $A(4, 3), B(4, 6), C(8, 6)$
> 2. The area of the original triangle is 1/2
> 3. The area of the new triangle is 6
> 4. The determinant of the original matrix gives you the scale factor that you will enlarge the area by when you complete the transformation. The determinant of the matrix is $12$ and $\frac{1}{2}\times 12=6$
> 
> This rule is written as: Area of image = Area of object $\times |\det(\mathbf{M})|$

