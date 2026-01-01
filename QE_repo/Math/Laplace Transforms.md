Chapter 6 in Erwin K.

Make a note of something, [[Fourier Transforms]], or try [the Importer](https://help.obsidian.md/Plugins/Importer)!

$$
F(s) = \mathcal{L}(f) = \int_0^\infty e^{-st}f(t)dt
$$
Chapter 6.1 pg. 204
##  Theorem 1: Linearity
The Laplace transform is a linear operation; that is, 
$$
\mathcal{L}[af(t) + bg(t)] = a\mathcal{L}[f(t)] + b\mathcal{L}[g(t)] 
$$
## Theorem 2: First Shifting 
$$
\mathcal{L}[e^{at}f(t)] = F(s-a)
$$
## Theorem 3: Existence 
If $f(t)$ is defined and piecewise continuous on every finite interval on the semi-axis $t\geq0$ and satisfies $|f(t)|\leq Me^{kt}$ (with some constants: $M,k$) $\forall t \geq 0$, then the Laplace transform exists for all $s>k$ 

---
Chapter 6.2 pg. 211
## Theorem 4: Derivatives
The first derivative
$$
\mathcal{L}[f']=s\mathcal{L}[f] - f(0)
$$
The second derivative
$$
\mathcal{L}[f'']=s^2\mathcal{L}[f] - sf(0) - f'(0)
$$
And generally speaking
$$
\mathcal{L}[f^{(n)}]=s^n\mathcal{L}[f] - s^{n-1}f(0) -s^{n-2}f'(0)-...- f^{n-1}(0)
$$

## Theorem 5: Integrals
$$
\mathcal{L} \left[\int^t_0f(\tau)d\tau \right] = \frac{1}{s}F(s)
$$
## Solutions to Diff. Eq.
Consider the function
$$
y'' + ay' + by = r(t); \hspace{0.5cm} y(0)=K_0, \hspace{0.25cm} y'(0)=0
$$
Then the transformed system 
$$
[s^2Y - sy(0) -y'(0)] + a[sY-y(0)] + bY = R(s)
$$
Rearrange it
$$
Y[s^2 + as + b] = (s+a)K_0 + K_1 + R(s)
$$
Define $Q\equiv (s^2 + as + b)^{-1}]$, which is the [[Transfer Functions]] of the system. Then,
$$
Y(s) = [(s+a)K_0 + K_1]Q(s) + R(s)Q(s)
$$
With some algebra, and knowledge of inverse transforms, then the system is solved for the given initial conditions. 

*Note:* the transfer function, $Q$, depends neither on $r(t)$ nor on the ICs. It is a function dependent only on the homogenous Diff. Eq. $f(t)=0$

---
Chapter 6.3 pg. 217

## Heaviside (Unit Step) Function
$$
u(t-a)\equiv
\begin{cases}
	0 & t<a\\
	1 & t>a
\end{cases}
$$
Which has the Laplace Transform
$$
\mathcal{L}[u(t-a)] = \frac{e^{-as}}{s}
$$

## Theorem 6: Second Shifting
Consider the function *shifted* by the unit step function
$$
\tilde f(t)=f(t-a)u(t-a)=
\begin{cases}
	0 & t<a \\
	f(t-a) & t>a 
\end{cases}
$$
Then the corresponding Laplace transform
$$
\mathcal{L}[\tilde f(t)] = e^{-as}F(s)
$$

---
Chapter 6.4 pg. 225

## Dirac delta function
The function is defined as
$$
\delta(t-a)= 
\begin{cases}
	\infty & t=a \\
	0 & else
\end{cases}
$$
It interacts with other functions with the effect
$$
\int_0^\infty g(t)\delta(t-a)dt = g(a)
$$
So the Laplace transform is given by
$$
\mathcal{L}[\delta(t-a)]=e^{-as}
$$
---
Chapter 6.5 pg. 232

## Theorem 7: [[Math/Convolution|Convolution]]
The convolution of two functions is given by 
$$
(f\circ g)(t)= \int_0^t f(\tau)g(t-\tau)d\tau
$$ 
$$
\mathcal{L}[(f\circ g)(t)] = \mathcal{L}[f(t)]\mathcal{L}[g(t)] = F(s)G(s) 
$$
That is, the Laplace transform of a convolution function is given by the product between the transform for the constituent functions independently

---

Chapter 6.6 pg. 238

## Differentiation of Laplace Functions
$$
\mathcal{L}[tf(t)] = -F'(s)=-\frac{dF}{ds}
$$
## Integration of Laplace Functions
$$
\mathcal{L}\left[\frac{f(t)}{t} \right] = \int_s^\infty F(\tilde s)d\tilde s
$$

# Basic Transforms

| $f(t)$    | $\mathcal L[f(t)]$   | $f(t)$                | $\mathcal{L}[f(t)]$            |
| --------- | -------------------- | --------------------- | ------------------------------ |
| $1$       | $1/s$                | $cos(\omega t)$       | $\frac{s}{s^2+\omega^2}$       |
| $t$       | $1/s^2$              | $sin(\omega t)$       | $\frac{\omega}{s^2+\omega^2}$  |
| $t^2$     | $2!/s^3$             | $cosh(a t)$           | $\frac{s}{s^2-a^2}$            |
| $t^n$     | $\frac{n!}{s^{n+1}}$ | $sinh(a t)$           | $\frac{a}{s^2-a^2}$            |
| $e^{at}$  | $\frac{1}{s-a}$      | $e^{at}cos(\omega t)$ | $\frac{s-a}{(s-a)^2+\omega^2}$ |
| $te^{at}$ | $\frac{1}{(s-a)^2}$  | $e^{at}sin(\omega t)$ | $\frac{s-a}{(s-a)^2+\omega^2}$ |


