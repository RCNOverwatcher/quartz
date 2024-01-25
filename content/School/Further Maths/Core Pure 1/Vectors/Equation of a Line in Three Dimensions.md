---
banner: "![[furthermaths.jpg]]"
---
# Equation of a Line in Three Dimensions

> [!Tip] Vectors in 3D
> $$\mathbf{r}=\mathbf{a}+\lambda \mathbf{b}$$
> - $\mathbf{a}$ is the position vector to start.
> - $\mathbf{b}$ is the direction vector that determines which direction we are travelling in.
> - $\lambda$ is the variable scalar that allows us to get to any point on our line.
> - $\mathbf{r}$ is a position vector of our final point on the line.

> [!Example]- Vectors Problem
> $l_{1}: \mathbf{r}=\begin{pmatrix}3 \\ 0 \\ -2\end{pmatrix}+\lambda \begin{pmatrix}1 \\ 1 \\ 0\end{pmatrix}$
> Find the vector equation of a line parallel to $l_{1}$ which passes through $(2, 5, 1)$
> $l_{2}: \mathbf{r}=\begin{pmatrix}2 \\ 5 \\ 1\end{pmatrix}+\lambda \begin{pmatrix}1 \\ 1 \\ 0 \end{pmatrix}$
> - This works because the start position is different, but the direcion vector is the same as $l_{1}$ which means they will be parallel.

> [!Example]- Another vectors problem 
> $l_{1}: \mathbf{r}=\begin{pmatrix}-1 \\ 0 \\ 3\end{pmatrix}+\lambda \begin{pmatrix}1 \\ 1 \\ 0\end{pmatrix}$
> Find the coordiantes of the points on $l_{1}$ which are a distance of 3 away from (3, 4, 4).
> 
> - Generic point on line: $\begin{pmatrix}-1+\lambda \\\lambda \\3\end{pmatrix}$
> - Point we are finding about: $(3, 4, 4)$
> - Distance between: $\sqrt{ (-1+\lambda-3)^3+(\lambda-4)^2+(3-4)^2 }=3$
> - $\lambda^2-8\lambda+12=0$
> - Solve for $\lambda$ gives us: $\lambda=2$ or $\lambda=6$
> - Sub back into our generic equation: 
> 	  If $\lambda=2 \to (1,2,3)$
>	If $\lambda=6\to(5,6,3)$

> [!Example]- The straight line has vector equation: $\mathbf{r}=(3i+2j-5k)+t(i-6j-2k)$. Given that the point $(a,b,0)$ is on $\mathbf{r}$, find $a$ and $b$
> - $\begin{pmatrix}3+t \\ 2-6t \\ -5-2t\end{pmatrix}$
> - $\therefore\begin{pmatrix}3+t \\ 2-6t \\ -5-2t\end{pmatrix}=\begin{pmatrix}a \\ b \\ 0\end{pmatrix}$
> - This means that $-5-2t=0$
> - Rearrange for $t$: $t=-\frac{5}{2}$
> - Solve simultaneously
> 	- $a=3+t$
> 	- $b=2-6t$
> 	- $a=\frac{1}{2}$
> 	- $b=17$

> [!Example]- The straight line $l$ has vector equation: $\mathbf{r}=(2i+5j-3k)+\lambda(6i-2j+4k)$. Show that another equation for $l$ is $\mathbf{r}=(8i+3j+k)+\mu(3i-j+2k)$
> - Directional part of $d_{1}$ = $\begin{pmatrix}6 \\ -2 \\ 4\end{pmatrix}$
> - Directional part of $d_{2}=\begin{pmatrix}3 \\ -1 \\ 2\end{pmatrix}$
> - $d_{1}=2d_{2}$
> - Since they are multiples of one another, they go in the same direction.
> - We choose a value of $\lambda = 0$: $r_{1}=\begin{pmatrix}2 \\ 5 \\ -3\end{pmatrix}$
> - We now need to find a value of $\mu$ that gives us $\begin{pmatrix}2 \\ 5 \\ -3\end{pmatrix}$
> - $\begin{pmatrix}2 \\ 5 \\ -3\end{pmatrix}=\begin{pmatrix}8+3\mu \\3-\mu \\1+2\mu\end{pmatrix}$
> - Choose one to solve: $8+3\mu=2$
> - $\mu=-2$
> - It works for the other two equation $\therefore$ it works.

> [!Info] A Cartesian Equation is an equation with only $x, y, z$ and nothing else (like $\lambda$ and $\mu$)
> If $\mathbf{a}=\begin{pmatrix}a_{1} \\a_{2} \\a_{3}\end{pmatrix}$ and $\mathbf{b}=\begin{pmatrix}b_{1} \\b_{2} \\b_{3} \\\end{pmatrix}$ and $\mathbf{r}=\mathbf{a}+\lambda \mathbf{b}$ is equation of a straight line, the Certesian form is $$\frac{x-a_{1}}{b_{1}}=\frac{y-a_{2}}{b_{2}}=\frac{z-a_{3}}{b_{3}}$$

> [!Example]- Find the Cartesian Equation of the line with equation $\mathbf{r}=\begin{pmatrix}2 \\ 5 \\ 0\end{pmatrix}+\lambda \begin{pmatrix}1 \\ 3 \\ -2\end{pmatrix}$
> $$\frac{x-2}{1}=\frac{y-5}{3}=\frac{z}{-2}$$

> [!Example]- Find the vector equation of the cartesian line equation $y=3x+2$
> $$\begin{pmatrix}0 \\2\end{pmatrix}+\lambda \begin{pmatrix}1 \\3\end{pmatrix}$$

> [!Example]- Find the vector equation of $\frac{x-2}{3}=\frac{y+5}{1}=\frac{z}{4}$
> - $a_{1}=2$
> - $a_{2}=-5$
> - $a_{3}=0$
> - $b_{1}=3$
> - $b_{2}=1$
> - $b_{3}=4$
> - $\begin{pmatrix}x \\ y \\ z\end{pmatrix}=\begin{pmatrix}2 \\ -5 \\ 0\end{pmatrix}+\lambda \begin{pmatrix}3 \\ 1 \\ 4\end{pmatrix}$

> [!Example]- Find the points where any of these vectors intersect 
> $$\mathbf{a}=\begin{pmatrix}4 \\0 \\-2\end{pmatrix}+\alpha \begin{pmatrix}-1 \\1 \\4\end{pmatrix}$$
> $$\mathbf{b}=\begin{pmatrix}1 \\3 \\10\end{pmatrix}+\beta \begin{pmatrix}-2 \\-1 \\2\end{pmatrix}$$
> $$\mathbf{c}=\begin{pmatrix}2 \\-1 \\0\end{pmatrix}+\gamma \begin{pmatrix}1 \\2 \\2 \end{pmatrix}$$
> 
> 1. $\begin{pmatrix}4-\alpha \\\alpha \\-2+4\alpha\end{pmatrix}=\begin{pmatrix}1-2\beta \\3-\beta \\10+2\beta\end{pmatrix}$
> 	$4-\alpha=1-2\beta$ (1)
> 	$\alpha=3-\beta$ (2)
> 	$-2+4\alpha=10-2\beta$ (3)
> $(1)+(2): 4=4-3\beta$
> $\beta=0$
> $\alpha=3$
> Therefore $\mathbf{a}$ and $\mathbf{b}$ intersect at point $(1, 3, 10)$
> ---
> This would now be done for pair $\mathbf{a}$ and $\mathbf{c}$ as well as pair $\mathbf{b}$ and $\mathbf{c}$

