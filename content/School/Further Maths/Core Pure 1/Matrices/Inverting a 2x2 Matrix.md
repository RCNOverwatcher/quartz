---
banner: "![[furthermaths.jpg]]"
---
# Inverting a 2x2 Matrix

> [!Info] Inverting a 2x2 matrix
> - We earlier saw that the inverse of a matrix $\mathbf{M}$, written as $\mathbf{M^{-1}}$ undoes the effect of a matrix.
> - This means that $\mathbf{MM^{-1}}=\mathbf{M^{-1}M}=\mathbf{I}$
> - This is because multiplying something by a matrix followed by multiplying by the inverse of that matrix, means the original point stays the same, which is the **same** as multiplying by the identity matrix.

> [!Tip] How to invert a 2x2 matrix
> - If $\mathbf{A}=\begin{pmatrix}a & b \\ c & d\end{pmatrix}$, then $\mathbf{A^{-1}}=\frac{1}{\det(A)}\begin{pmatrix}d & -b \\ -c & a\end{pmatrix}$
> 
> - $\mathbf{A^{-1}}$ is the inverse of $\mathbf{A}$,  such that if $\mathbf{A}x=y$, $\mathbf{A^{-1}}y=x$
> - $\mathbf{AA^{-1}}=\mathbf{A^{-1}A}=\mathbf{I}$
> - det$(\mathbf{A})=|\mathbf{A}|=ad-bc$

> [!Example]- Exercises on inverting a 2x2 matrix
> 1. $\mathbf{A}=\begin{pmatrix}2 & 0 \\ 0 & 2\end{pmatrix}$
> $\mathbf{A^{-1}}=\frac{1}{4}\begin{pmatrix}2 & -0 \\ -0 & 2\end{pmatrix}$
> $\mathbf{A^{-1}}=\begin{pmatrix}\frac{1}{2} & 0 \\0 & \frac{1}{2}\end{pmatrix}$
> 
> 2. $\mathbf{B}=\begin{pmatrix}1 & 2 \\3 & 4\end{pmatrix}$
> $\mathbf{B^{-1}}=\frac{1}{4-6}\begin{pmatrix}-4 & 2 \\ 3 & -1\end{pmatrix}$
> $\mathbf{B^{-1}}=\frac{1}{2}\begin{pmatrix}-4 & 2 \\3 & -1\end{pmatrix}$

> [!Example]- Matrix Proofs involving inverse
> 1. If $\mathbf{P}$ and $\mathbf{Q}$ are non-singular matricies, prove that $(\mathbf{PQ})^{-1}=\mathbf{Q^{-1}P^{-1}}$
> - $\mathbf{(PQ)^{-1}}=\mathbf{C}$
> - $(\mathbf{PQ})\mathbf{C}=\mathbf{I}$
> - $\mathbf{P^{-1}PQC=P^{-1}I}$
> - $\mathbf{IQC=P^{-1}}$
> - $\mathbf{QC=P^{-1}}$
> - $\mathbf{IC=Q^{-1}P^{-1}}$
> - $\mathbf{C=Q^{-1}P^{-1}}$
> - $\mathbf{(QP)^{-1}=Q^{-1}P^{-1}}$
> 
> 2. If $\mathbf{A}$ and $\mathbf{B}$ are non-singular matricies such that $\mathbf{BAB=I}$, prove that $\mathbf{A=B^{-1}B^{-1}}$
> - $\mathbf{BAB=I}$
> - $\mathbf{B^{-1}BAB=B^{-1}I}$
> - $\mathbf{IAB=B^{-1}}$
> - $AB=B^{-1}$
> - $\mathbf{ABB^{-1}=B^{-1}B^{-1}}$
> - $\mathbf{AI=B^{-1}B^{-1}}$
> - $\mathbf{A=B^{-1}B^{-1}}$


