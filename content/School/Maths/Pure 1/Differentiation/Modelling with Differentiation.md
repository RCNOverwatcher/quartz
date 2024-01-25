---
banner: "![[maths.jpg]]"
---
# Modelling with Differentiation

> [!Info] The root of Differentiation
> - Up to now, we've had y in terms of x where $\frac{dy}{dx}$ means the rate at which y changes in respect to x.
> - But we can use similar gradient function notation for other physical quantities.
> - E.G. A sewage container fills at a rate of $20cm^3$ per second. To describe this, we can use $\frac{dV}{dt}=20cm^3/s$

> [!Example]- Cuboid Problem
> **INFO:**
> - Limitations: has to be a cuboid with a horizonal base with no top, must be made of $54cm^2$ of sheet metal, must have two squares for sides.
> - Surface area: $54cm^2$
> - Side lengths of side squares: $x$
> 
>**EQUATIONS:**
>-  Volume: $l\times w\times h$ = $x^2+w$
>- Surface Area: $2x^2+3xw \to2x^2+3xw=54$
>
>**REARRANGING:**
>- $3xw=54-2x^2$
>- $w=\frac{18}{x}-\frac{2x}{3}$
>
>**SUB BACK IN:**
>- $V=x^2\times \left( \frac{18}{x}-\frac{2x}{3} \right)$
>- $V=18x-\frac{2x^3}{3}$
>- $V=18x-\frac{2}{3}x^3$
>
>
>**FINDING THE OPTIMAL VALUE:**
>- Differentiate the function: $18x-\frac{2x^3}{3} \to 18-2x^2$
>- $18-2x^2=0$
>- $x=^+_{-}3$
>- Sub back in to find the y value (or in this case, the volume)
>- $V=36$

> [!Example]- Another Cuboid Problem
>  **INFO:**
> - Limitations: has to be a cuboidwith volume of $81cm^3$
> - Surface area: $10x^2$
> - Side lengths of side squares: $x$
> 
>**EQUATIONS:**
>-  Volume: $V=2x^2y$
>- Length: $12x+4y$
>- $y=\frac{81}{2x^2}$
>
>**REARRANGING:**
>- $L=12x+\frac{162}{x^2}$
>- $\frac{dL}{dx}=12-324x^{-3}$
>- $= 12-\frac{324}{x^3}$
>
>**SET TO 0:**
>- $12-\frac{324}{x^3}=0$
>- $x^3=\frac{324}{12}=27$
>- $x=3$
>
>**FINDING THE OPTIMAL/MINIMUM VALUE:**
>- $L_{\text{min}}=12(3)+\frac{162}{9}=54cm$
>- $\frac{d^2L}{dx^2}=972x^{-4}$
>- When $x=3$:
>- $\frac{d^2L}{dx^2}=\frac{972}{3^4}>0\therefore$ it is a minimum.

> [!Example]- Rectangular base with a Semicircle top Problem
> **INFO:**
> - Perimeter: 40cm
> - $\pi r+2r+x=40$
> - $A=\frac{\pi r^2}{2}+2rx$
> - $x=40-\pi r-2r$
> - $A=\frac{\pi r^2}{2}+2r(40-\pi r-2r)$