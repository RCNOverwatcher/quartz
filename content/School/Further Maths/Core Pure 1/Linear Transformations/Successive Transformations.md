---
banner: "![[furthermaths.jpg]]"
---
# Successive Transformations

> [!Info] Applying multiple transformations 
>-  Original co-ords =  $x$
> - New co-ords = $y$
> - When I apply matrix $\mathbf{A}$ to the co-ords $x$, this can be written as $\mathbf{A}x=y$
> - If I apply matrix $\mathbf{A}$ and then matrix $\mathbf{B}$, then this can be written as $\mathbf{BA}x=y$
>-  You can either multiply out the $\mathbf{BA}$ matricies first and then do that multiplied by $x$, or you could do $\mathbf{B}\times x$ and then that $\times \mathbf{A}$

> [!Example]- Doing a successive transformation 
> - $\begin{pmatrix}2 & 0 \\ 0 & 1\end{pmatrix}\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}\begin{pmatrix}x \\ y\end{pmatrix}=\begin{pmatrix}2 & 0 \\ 0 & 1\end{pmatrix}\begin{pmatrix}y \\ x\end{pmatrix}=\begin{pmatrix}2y \\ x\end{pmatrix}$
> - $\begin{pmatrix}2 & 0 \\ 0 & 1\end{pmatrix}\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}\begin{pmatrix}x \\ y\end{pmatrix}=\begin{pmatrix}0 & 2 \\ 1 & 0\end{pmatrix}\begin{pmatrix}x \\ y\end{pmatrix}$

> [!Example]- Represent as a single matrix the transformation representing a reflection in the line $y=x$ followed by a stretch in the x-axis by a factor of 4.
> - $y=x$ matrix $=\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}$
> - Stretch by 4 in x axis matrix = $\begin{pmatrix}4 & 0 \\ 0 & 1\end{pmatrix}$
> - $\begin{pmatrix}4 & 0 \\ 0 & 1\end{pmatrix}\times\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}=\begin{pmatrix}0 & 4 \\ 1 & 0\end{pmatrix}$

> [!Example]- Represent as a single matrix the transformation representing a rotation 90$^\circ$ anticlockwise about the point (0, 0) followed by a reflection in the line $y=x$
> -  $y=x$ matrix $=\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}$
> - Rotation 90$^\circ$ anticlockwise matrix = $\begin{pmatrix}0 & -1  \\ 1 & 0\end{pmatrix}$
> - $\begin{pmatrix}0 & 1 \\ 1 & 0\end{pmatrix}\times \begin{pmatrix}0 & -1  \\ 1 & 0\end{pmatrix}=\begin{pmatrix}1 & 0 \\ 0 & -1\end{pmatrix}$

> [!Example]- Exam Question 
> 1. P: Matrix for 90$^\circ$ anticlockwise = $\begin{pmatrix}0 & -1 \\ 1 & 0\end{pmatrix}$
> 2. Q: Matrix for the reflection $y=-x$: $\begin{pmatrix}0 & -1  \\ -1 & 0\end{pmatrix}$
> 3. R = QP: $\begin{pmatrix}0 & -1 \\ -1 & 0\end{pmatrix}\times \begin{pmatrix}0 & -1  \\ 1 & 0\end{pmatrix}=\begin{pmatrix}-1 &0 \\ 0 & 1\end{pmatrix}$
> 4. Reflection in the y-axis

