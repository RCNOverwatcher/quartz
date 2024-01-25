---
banner: "![[furthermaths.jpg]]"
---
# Linear Transformations in two dimensions

> [!Info] Linear Transformations: True or False?
> 1. We can represent a translation using a matrix. **FALSE**. (Matrices can only be used for multiplying points)
> 2. We can convert a 3d coordinate into a 2d coordinate. **TRUE**. If we set the Z componant to 0 then it will become a 2d point.

> [!Example]- Reversing linear transformations
> - $\begin{pmatrix}? & ? \\ ? & ?\end{pmatrix}\begin{pmatrix}x \\ y\end{pmatrix}=\begin{pmatrix}2y+x \\ 3x\end{pmatrix}$
> - $\begin{pmatrix}1x+2y \\ 3x+0y\end{pmatrix}$
> - $\begin{pmatrix}1 & 2 \\ 3  & 0\end{pmatrix}$

> [!Example]- Carrying out linear transformations
> $\begin{pmatrix}-1 & 2 \\ 2 & 1\end{pmatrix}\begin{pmatrix}x \\ y\end{pmatrix}=\mathbf{S}$
> - $(1, 1) \to (1, 3 )$
> - $(3, 1)\to(-1,7)$
> - $(3,3)\to(3, 9)$
> - $(1, 3)\to(5, 5)$

> [!Info] Determining a Matrix for a specific transformations
> 1. Reflection in the y axis: $\begin{pmatrix}-1 & 0 \\ 0 & 1\end{pmatrix}$
> 2. Reflection in the x axis: $\begin{pmatrix}1 & 0 \\ 0 & -1\end{pmatrix}$
> 3. Rotation of 90$^{\circ}$ about the origin clockwise: $\begin{pmatrix} 0 & 1 \\ -1 & 0\end{pmatrix}$
> 4. Rotation of 90$^{\circ}$ about the origin anticlockwise: $\begin{pmatrix}0 & -1 \\ 1 & 0\end{pmatrix}$
> 5. Rotation of 180$^{\circ}$:$\begin{pmatrix}-1 & 0 \\0 & -1\end{pmatrix}$
> 6. Reflection in the line $y=x$: $\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}$
> 7. Reflection in the line $y=-x$: $\begin{pmatrix}0 & -1 \\ -1 & 0\end{pmatrix}$
> 8. Enlargement of 2:$\begin{pmatrix}2 & 0 \\ 0 & 2\end{pmatrix}$

> [!Tip] Unit Vectors
> - The two unit vectors used are (0, 1) and (1, 0)
> - These are labelled as $i$ and $j$
> - You can take a shortcut by using unit vectors.
>  ![[Pasted image 20230112114315.png|300]]
>  - As shown by this image, if we rotate the unit vector (0, 1) 90$^\circ$, then we get the new point, (1, 0)
>  - Combining these two vectors gives us the matrix we need to transform the point.
>  - $\begin{pmatrix}0 \\ 1\end{pmatrix}+\begin{pmatrix}1  \\ 0\end{pmatrix}=\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}$
