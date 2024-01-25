---
banner: "![[furthermaths.jpg]]"
---
# Multiplying and dividing complex numbers

> [!Info] Method 
> - If $z_{1}=r_{1}e^{i\theta_{1}}$ and $z_{2}=r_{2}e^{i\theta_{2}}$ then:
> - $z_{1}z_{2}=r_{1}r_{2}e^{i(\theta_{1}+\theta_{2})}$
> - $\frac{z_{1}}{z_{2}}=\frac{r_{1}}{r_{2}}e^{i(\theta_{1}-\theta_{2})}$

> [!Example]
> $3\left( \cos\frac{5\pi}{12}+i\sin\frac{5\pi}{12} \right)\times4\left( \cos \frac{\pi}{12}+i\sin \frac{\pi}{12} \right)$
> $=12\left( \cos \frac{\pi}{2}+i\sin \frac{\pi}{2} \right)$
> $=12(0+(i\times1))$
> $=12i$

> [!Abstract] Find $z^5$
> - Modulus of 2
> - Argument of $\frac{1}{3}\pi$
> - Written as $2\left( \cos \frac{1}{6}\pi+\sin \frac{1}{6}\pi \right)$
> - Or as $(2e^{i \frac{\pi}{6}})^5$
> - Which equals $32 e^{i \frac{5\pi}{6}}$

> [!Example]- $z^n=r^n(\cos n\theta+i\sin n\theta)$
> - Show true for $n=1$
> 	- $z^1=r^1(\cos\theta+i\sin\theta)$
> - Assume true for $n=k$
> 	- $z^k=r^k(\cos k\theta+i\sin k\theta)$
> - Show true for $n=k+1$
> 	- $z^{k+1}=r^{k+1}(\cos (k+1)\theta+i\sin (k+1)\theta)$
> 	- $z^{k+1}=z^k+z$
> 	- $=r^k(\cos k\theta+i\sin k\theta)\times r(\cos\theta+i\sin\theta)$
> 	- $=r^{k+1}(\cos (k\theta+\theta)+i\sin(k\theta+\theta))$
> 	- $=r^{k+1}(\cos ((k+1)\theta)+i\sin((k+1)\theta))$
> 	- Hence true for all positive n.
