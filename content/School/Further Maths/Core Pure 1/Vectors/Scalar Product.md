---
banner: "![[furthermaths.jpg]]"
---
# Scalar Product

> [!Info] Scalar Product 
> - The scalar product (dot product) $\mathbf{a} \text{  }\mathbf{b}$ of two vectors is the sum of the products of the components.
> - $$\mathbf{a} \text{  } \mathbf{b}=\sum a_{i}b_{i}$$

> [!Info] Finding angles between Vectors
> - We can find the unit vector of any vector by dividing the vector by it's modulus.
> - And the unit vector of $\mathbf{\hat{a}} \times\mathbf {\hat{b}}$ = $\cos\theta$ of the angle formed between the two vectors.
> - $\frac{\mathbf{a}}{|a|}\times \frac{\mathbf{b}}{|b|}=\cos\theta$
> - $\frac{1}{|a||b|}(\mathbf{a}\times \mathbf{b})=\cos\theta$
> - $\mathbf{a}\times \mathbf{b}=|a||b|\cos\theta$

> [!Info]- Proof for Scalar Product (long)
> - $|\hat{b}-\hat{a}|^2=|\hat{a}|^2+|\hat{b}|^2-2|\hat{a}||\hat{b}|\cos\theta$
> - $|\hat{b}-\hat{a}|^2=1+1-2\cos\theta$
> - $(\sqrt{ (b_{1}-a_{1}^2)+(b_{2}-a_{2})^2+(b_{3}-a_{3})^2 })^2=2-2\cos\theta$
> - $b_{1}^2-2b_{1}a_{1}+a_{1}^2+b_{2}^2-2b_{2}a_{2}+a_{2}^2+b_{3}^2-2b_{3}a_{3}+a_{3}^2=2-2\cos\theta$
> - $b_{1}^2+b_{2}^2+b_{3}^2+a_{1}^2+a_{2}^2+a_{3}^2-2(b_{1}a_{1}+b_{2}a_{2}+b_{3}a_{3})=2-2\cos\theta$
> - $|b|^2+|a|^2-2\hat{a}\times \hat{b}=2-2\cos\theta$
>  - $2-2\hat{a}\times \hat{b}=2-2\cos\theta$
>  - $\hat{a}\times \hat{b}=\cos\theta$

> [!Example]- Find the acute angle between the vectors $\mathbf{a}=\begin{pmatrix}5 \\ 3 \\ 1\end{pmatrix}$ and $\mathbf{b}=\begin{pmatrix}1 \\ 0 \\ 5\end{pmatrix}$
> - Times the two vectors together and divide by the product of the moduli.
> - $\frac{(5\times1)+(3\times0)+(1\times5)}{|a|\times |b|}$
> - $\frac{(5\times1)+(3\times0)+(1\times5)}{\sqrt{ 35 }\times \sqrt{ 26 }}$
> - $=0.331496\dots$
> - $\cos^{-1}(0.331496)=70.64^\circ$

> [!Example]- Find the angle between the vectors $\mathbf{a}=\begin{pmatrix}2 \\ 4 \\ -1\end{pmatrix}$ and $\mathbf{b}=\begin{pmatrix}0 \\ 1 \\ 8\end{pmatrix}$
> - $\frac{(2\times0)+(4\times1)+(-1\times8)}{|a|\times |b|}$
> - $\frac{(2\times0)+(4\times1)+(-1\times8)}{\sqrt{ 19 }\times \sqrt{ 65 }}=-0.108266$
> - $\cos^{-1}(-0.108266)=96.215$

> [!Info]- Perpendicular vectors
> - If two vectors are perpendicular, then $\mathbf{a}\times \mathbf{b}=0$
> - 