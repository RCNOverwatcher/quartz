---
banner: "![[maths.jpg]]"
---
# The Trapezium Rule

> [!Tip] The Trapezium Rule 
> $$\int ^b_{a}y \, dx =\frac{1}{2}h(y_{0}+2(y_{1}+y_{2}+y_{3}+y_{n-1})+y_{n})$$
> 
> $$h=\frac{b-a}{n}$$
> 

> [!Example] Example
> Line is $y=\sec x$ between $0$ and $\frac{\pi}{3}$
> 
> | $x$ | $0$ | $\frac{\pi}{12}$ | $\frac{\pi}{6}$  | $\frac{\pi}{4}$  | $\frac{\pi}{3}$ |
> |---|---|-------|-------|-------|------|
> | $y$ | $1$ | $1.035$ | $1.155$ | $1.414$ | $2$    |
>
>- Using trapezium rule:
>
> $$\int _{a}^by \, dx = \frac{1}{2}\times \frac{\pi}{12}[1+2(1.035+1.155+1.414)+2]=\frac{\pi}{24}[10.208]=1.336\dots=1.34\text{ to 2dp}$$


> [!Example] Ex 11I Q1
> Line is $y=\sqrt{ 1+\tan x }$ between $0$ and $\frac{\pi}{3}$
> 
> | $x$ | $0$ | $\frac{\pi}{12}$ | $\frac{\pi}{6}$  | $\frac{\pi}{4}$  | $\frac{\pi}{3}$ |
> |---|---|-------|-------|-------|------|
> | $y$ | $1$ | $1.1233$ | $1.2559$ | $1.3362$ | $1.6529$ |
>
>- Using trapezium rule and values for $0$, $\frac{\pi}{6}$ and $\frac{\pi}{3}$:
>
> $$\int _{a}^by \, dx = \frac{1}{2}\times \frac{\pi}{6}(1+2(1.2559)+1.6529)=\frac{\pi}{12}\times5.1647=1.3521\dots=1.352\text{ to 4sf}$$
> 
> - Using trapezium rule and values for $0$, $\frac{\pi}{12}$, $\frac{\pi}{6}$, $\frac{\pi}{4}$ and $\frac{\pi}{3}$:
> 
> $$\int _{a}^by \, dx = \frac{1}{2}\times \frac{\pi}{12}(1+2(1.1233+1.2559+1.3362)+1.6529)=\frac{\pi}{24}\times_{1}0.0837=1.31995\dots=1.320\text{ to 4sf}$$
> 


> [!Example] Ex 11I Q2
> Line is $y=\cos\frac{5\theta}{2}$ between $-\frac{\pi}{5}$ and $\frac{\pi}{5}$
> 
> | $x$ | $-\frac{\pi}{5}$ | $-\frac{\pi}{10}$ | $0$  | $\frac{\pi}{10}$  | $\frac{\pi}{5}$ |
> |---|---|-------|-------|-------|------|
> | $y$ | $0$ | $\frac{\sqrt{ 2 }}{2}$ | $1$ | $\frac{\sqrt{ 2 }}{2}$ | $0$ |
> 
> - Using trapezium rule and all values in the table:
> 
> $$\int _{a}^by \, dx = \frac{1}{2}\times\frac{\pi}{10}\left( 2\left( \frac{\sqrt{ 2 }}{2}+1+\frac{\sqrt{ 2 }}{2} \right) \right)=\frac{\pi}{10}(1+\sqrt{ 2 })=0.75845\dots=0.758\text{ to 3dp}$$
> 
> - Trapezium rule produces an underestimate due to trapezium lines going under the curve
>
> --- 
> 
> $$\int ^{\frac{\pi}{5}}_{-\frac{\pi}{5}} \cos\frac{5\theta}{2}\, dx =\left[ \frac{2}{5}\sin\frac{5\theta}{2} \right]^{\frac{\pi}{5}}_{-\frac{\pi}{5}}=\frac{2}{5}--\frac{2}{5}=\frac{4}{5}=0.8$$
> 
> 
> ---
> $5.25\% \text{ error}$

