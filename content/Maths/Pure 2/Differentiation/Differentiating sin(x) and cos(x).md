---
banner: "![[maths.jpg]]"
---
# Differentiating $sin(x)$ and $cos(x)$

> [!Info] Differentiating sin(x) and cos(x)
> - Using small angle approximations:
> 	- $\sin(x)=x$
> 	- $\cos(x)=1-\frac{1}{2}x^2$
> - This means that $\lim_{ h \to 0 }\frac{\sin(h)}{h}=\lim_{ h \to 0 }\frac{h}{h}=1$ 
> - and $\lim_{ h \to 0 }\frac{\cos h-1}{h}=\lim_{ h \to 0 }\frac{1-\frac{1}{2}h^2-1}{h}=\lim_{ h \to 0 }-\frac{1}{2}h=0$

> [!Example] $\sin(x)$
> - Let $f(x)=\sin(x)$
> - $f^{'}(x)=\lim_{ h \to 0 }\frac{f(x+h)-f(x)}{h}$
> - $=\lim_{ h \to 0 }\frac{\sin(x+h)-\sin(x)}{h}$
> - $=\lim_{ h \to 0 }\frac{\sin x\cos h+\sin h\cos x-\sin x}{h}$
> - $=\lim_{ h \to 0 }\frac{\sin x(\cos h-1)}{h}+\frac{\cos x\sin h}{h}$
> - $=\lim_{ h \to 0 }\frac{\sin x\left( 1-\frac{h^2}{2}-1 \right)}{h}+\frac{\cos x\times h}{h}$
> - $=\lim_{ h \to 0 }\frac{h}{2}\sin x+\cos x$
> - $=\cos x$

> [!Example] $\cos (x)$
> - Let $f(x)=\sin(x)$
> - $f^{'}(x)=\lim_{ h \to 0 }\frac{f(x+h)-f(x)}{h}$
> - $f^{'}(x)=\lim_{ h \to 0 }\frac{\cos x\cos h-\sin x\sin h-\cos x}{h}$
> - $=\lim_{ h \to 0 }\frac{\cos x(\cos h-1)}{h}-\frac{\sin x\sin h}{h}$
> - $=\lim_{ h \to 0 }\frac{\cos(x)\left( 1-\frac{h^2}{2}-1 \right)}{h}-\frac{\sin x \times h}{h}$
> - $=\lim_{ h \to 0 }-\frac{h}{2}\cos x-\sin x$
> - $=-\sin x$

> [!Info] If there is a $k$ in front...
> - $\frac{d}{dx}(\sin kx)=k\cos kx$
> - $\frac{d}{dx}(\cos kx)=-k\sin kx$

> [!Example] Examples 
> 1. $\frac{d}{dx}(\sin3x)=3\cos3x$
> 2. $\frac{d}{dx}(5x)=-5\sin 5x$
> 3. $\frac{d}{dx}(3\sin 5x)=3(5\cos5x)=15\cos 5x$
> 4. $\frac{d}{dx}\left( -\frac{2}{3}\cos\frac{1}{2}x \right)=-\frac{2}{3}\left( -\frac{1}{2}\cos\frac{1}{2}x \right)=\frac{1}{3}\cos\frac{1}{2}x$

## Finding stationary points 

> [!Example] Find the stationary points of $y=\frac{1}{2}x-\cos 2x, 0\leq x\leq \pi$
> $\frac{d}{dx}=\frac{1}{2}+2\sin2x$
> $\frac{1}{2}+2\sin2x=0$
> $2\sin2x=-\frac{1}{2}$
> $\sin2x=-\frac{1}{4}$
> $2x=\sin^{-1}\left( -\frac{1}{4} \right)$
> $2x=-14.477$
> $x=7.238$

> [!Example]- Exercise 9a
> 1a. 
> - Let $f(x)=\sin(x)$
> - $f^{'}(x)=\lim_{ h \to 0 }\frac{f(x+h)-f(x)}{h}$
> - $f^{'}(x)=\lim_{ h \to 0 }\frac{\cos x\cos h-\sin x\sin h-\cos x}{h}$
> - $=\lim_{ h \to 0 }\frac{\cos x(\cos h-1)}{h}-\frac{\sin x\sin h}{h}$
> - $=\lim_{ h \to 0 }\frac{\cos h-1}{h}\cos x-\frac{\sin h}{h}\sin x$
> 1b. 
> - $=\lim_{ h \to 0 }\frac{\cos h-1}{h}\cos x-\frac{\sin h}{h}\sin x$
> - $=\lim_{ h \to 0 }\frac{1-\frac{h^2}{2}-1}{h}\cos x-\frac{h}{h}\sin x$
> - $=\lim_{ h \to 0 }-\frac{h}{2}\cos x-\sin x$
> - $=-\sin x$
> ---
> 2. 
> 	a) $\frac{dy}{dx}2\cos x=-2\sin x$
> 	b) $\frac{dy}{dx}2\sin \frac{1}{2}x=\cos\frac{1}{2}x$
> 	c) $\frac{dy}{dx}\sin8x=8\cos8x$
> 	d) $\frac{dy}{dx}6\sin\frac{2}{3}x=4\cos\frac{2}{3}x$
> ---
> 3. 
>    a) $\frac{dy}{dx}2\cos x=-2\sin x$
>    b) $\frac{dy}{dx}6\cos\frac{5}{6}x=-5\sin\frac{5}{6}x$
>    c) $\frac{dy}{dx}4\cos\frac{1}{2}x=-2\sin\frac{1}{2}x$
>    d) $\frac{dy}{dx}3\cos2x=-6\sin2x$
>---
>4. 
>   a) $\frac{dy}{dx}\sin2x+\cos3x=2\cos 2x-\sin 3x$
>   b) $\frac{dy}{dx}2\cos4x-4\cos x+2\cos7x=-8\sin4x+4\sin x-14\sin7x$
>   c) $\frac{dy}{dx}x^2+4\cos3x=2x-12\sin3x$
>   d) $\frac{dy}{dx}\frac{1}{x}+x\sin5x=-\frac{1}{x^2}+10x\cos5x$
> ---
> 5. $\frac{dy}{dx}x-\sin3x=1-3\cos3x$
>    $1-3\cos3x=0$
>    $\cos3x=\frac{1}{3}$
>    $x=0.41$
>    $x=1.68$
>    $x=2.50$
>---
>6. $\frac{dy}{dx}2\sin4x-4\cos2x$
> $=8\cos4x+8\sin2x$
> $=8\cos2\pi+8\sin \pi$
> $=8+0$
> $=8$

### Equations of Tangents 

> [!Example]- Find the equation of the tangent to $y=2\sin(2x)$ at the point where $x=\frac{\pi}{6}$
> - $2\sin \frac{\pi}{3}=\sqrt{ 3 }$
> - Co-ordinates are $\left( \frac{\pi}{6},\sqrt{ 3 } \right)$
> - $\frac{dy}{dx}=4\cos(2x)$
> - gradient: $4\cos \frac{\pi}{3}=2$
> - $y-\sqrt{ 3 }=2\left( x-\frac{\pi}{6} \right)$
> - $y-\sqrt{ 3 }=2x-\frac{\pi}{3}$
> - $y=2x+\sqrt{ 3 }+\frac{\pi}{3}$

