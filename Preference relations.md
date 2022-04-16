---
aliases: preferences, preference
---

## Possible properties of preference relations

- A preference relation is **complete** if $x \succeq y$ or $y \succeq x$ for all $x, y \in X$.
- A preference relation is **reflexive** if $x \succeq x$ for all $x \in X$.
- A preference relation is **transitive** if $x \succeq y$ and $y \succeq z$ implies $x \succeq z$.
- A preference relation is **symmetric** if $x \succeq y \Rightarrow y \succeq x$ for all $x, y \in X$.

A preference relation is called **rational** if it is **complete** and **transitive**.

A preference relation is called an **ordering** if it is **complete**, **reflexive** and **transitive**.

A preference relation $\succeq$ on $X$ is **monotone** if $x \in X$ and $y \gg x$ implies $y \succ x$.
It is **strongly monotone** if $y \geq x$ and $x \neq y$ imply that $y \succ x$.

A preference relation is **locally non-satiated** if in every neighborhood of $x$ there exists a $y$ s.t. $y \succ x$.

A preference relation is **convex** if $\lambda x+(1-\lambda)y \succeq z$ if $x \succeq z$ and $y \succeq z$. This is equivalent to the [[Contour sets|upper contour set]] being a convex set.

A preference relation is **continuous** if all upper and lower [[Contour sets|contour sets]] are closed in $X$.

Source: Mas-Colell, Microeconomic Theory, Ch 3