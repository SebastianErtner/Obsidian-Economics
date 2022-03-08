# CES utility function

The following is an example of a utility function with constant [[Elasticty of substitution|elasticty of substitution]]:

$$u(x) = [x_1^s+x_2^s]^{1/s}$$
Proof:
$$E_{12} = \frac{\frac{d(c_1/c_2)}{(c_1/c_2)}}{\frac{d(p_1/p_2)}{(p_1/p_2)}}$$

There are two edge cases:

+ $s \rightarrow 0$:
	+ Cobb Douglas
+ $s \rightarrow -\infty$
	+ Leontief

[[Demand function#Walrasian Demand|Walrasian demand]]:

$$\partial u(x)/\partial x_i = (1/s)[x_1^s+x_2^s]^{(1-s)/s}sx_i^{s-1} = [x_1^s+x_2^s]^{(1-s)/s}x_i^{s-1}$$

$MRS = (x_1/x_2)^{s-1} = p_1/p_2$
$x_1/x_2 = (p_1/p_2)^\frac{1}{s-1}$

$p_1x_1+p_2x_2 = M$
$$
\begin{align}
p_1(p_1/p_2)^\frac{1}{s-1}x_2+p_2x_2 &= M\\
(p_1^\frac{s}{s-1}p_2^\frac{1}{1-s}+p_2)x_2 &= M\\
(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})p_2^\frac{1}{1-s}x_2 &= M\\
x_2(p,M) &= \frac{p_2^\frac{1}{s-1}M}{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})}
\end{align}
$$
By symmetry: 
$$x_1(p,M) = \frac{p_1^\frac{1}{s-1}M}{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})}$$
[[Indirect utility function]]:
$$
\begin{align}
v(p,M) &= [\frac{p_1^\frac{s}{s-1}M^s}{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})^s}+\frac{p_2^\frac{s}{s-1}M^s}{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})^s}]^{1/s}\\
v(p,M) &= [\frac{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})M^s}{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})^s}]^{1/s}\\
v(p,M) &= [\frac{M^s}{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})^{s-1}}]^{1/s}\\
v(p,M) &= \frac{M}{(p_1^\frac{s}{s-1}+p_2^\frac{s}{s-1})^\frac{s-1}{s}}\\
\end{align}$$

Elasticity of substitution:
$$\sigma = - \frac{\partial(x_1/x_2)}{\partial(p_1/p_2)}\frac{(p_1/p_2)}{(x_1/x_2)}$$
With $x_1/x_2 = (p_1/p_2)^\frac{1}{s-1}$

$$\sigma = -\frac{1}{s-1}(p_1/p_2)^{\frac{1}{s-1}-1}\frac{(p_1/p_2)}{(p_1/p_2)^\frac{1}{s-1}} = -\frac{1}{s-1} = \frac{1}{1-s}$$

