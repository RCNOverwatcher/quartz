---
banner: "![[furthermaths.jpg]]"
---
# Points of Intersection

> [!Info] Points of Intersection 
> - If two lines are parallel, then their direction vectors will be multiples of one another.
> - If they are the same line, then the position vector of one vector has to be on the same line as the other vector **and** their direction vectors have to be the same or multiplied by a scalar.

> [!Tip] Solving points of intersection 
> - First, write out two parts of each vector as single vectors.
> - Then you solve the equations simultaneously using the x and y components.
> - Once you find values for $\lambda$ and $\mu$, sub them into the z component. If these values work, then they two lines intersect.
> - Finally, sub in either $\lambda$ or $\mu$ to find the point of intersection.

> [!Example]- The line $l_{1}$ has equation $\mathbf{r}=\begin{pmatrix}1 \\ 0 \\ -1\end{pmatrix}+\lambda \begin{pmatrix}1 \\ 1 \\ 0\end{pmatrix}$. The line $l_{2}$ has equation $\mathbf{r=\begin{pmatrix}1 \\ 3 \\ 6\end{pmatrix}}+\mu \begin{pmatrix}2 \\ 1 \\ -1\end{pmatrix}$. Show that these lines do not intersect.
> - Multiply out:
> - $l_{1}=\begin{pmatrix}1+\lambda \\ \lambda \\ -1\end{pmatrix}$
> - $l_{2}=\begin{pmatrix}1+2\mu \\3+\mu \\6-\mu \end{pmatrix}$
> 
> - Use simultaneous equations:
> - $1+\lambda=1+2\mu$
> - $\lambda=3+\mu$
> 
> - $\lambda=6$
> - $\mu=3$
> 
> - See if it works for $z$:
> - $6-3=-1$
> - $3 \neq-1$
> 
> - Therefore points do not intersect.

> [!Example]- Find the point of intersection between: $l:\mathbf{r}=\begin{pmatrix}-1 \\ 1 \\ -5\end{pmatrix}+\lambda \begin{pmatrix}1 \\ 1 \\ 2\end{pmatrix}$ and $\Pi:\mathbf{r}\times \begin{pmatrix}1 \\ 2 \\3\end{pmatrix}=4$
> - Sub in $\mathbf{r}$
> - $\begin{pmatrix}-1+\lambda \\1+\lambda \\-5+2\lambda \end{pmatrix}\times \begin{pmatrix}1 \\ 2 \\ 3\end{pmatrix}=4$
> - Rearrange to find $\lambda$
> - $-1+\lambda+2+2\lambda-15+6\lambda=4$
> - $-14+9\lambda=4$
> - $9\lambda=18$
> - $\lambda=2$
> 
> - Point of intersection:
> - $\begin{pmatrix}-1+(2) \\1+(2) \\-5+2(2) \end{pmatrix}=\begin{pmatrix}1  \\3\\-1\end{pmatrix}$