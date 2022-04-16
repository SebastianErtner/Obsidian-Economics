## Maximal element
For a given [[Preference relations|preference relation]] $R$ on $X$ and set $S \subset X$ the element $x \in S$ is a maximal element in $S$, if $\neg yPx$ for all $y \in S$. The set of all maximal elements in $S$ is $M_R(S)$.

## Best element
For a given [[Preference relations|preference relation]] $R$ on $X$ and set $S \subset X$ the element $x \in S$ is a best element in $S$, if $xRy$ for all $y \in S$. The set of all best elements in $S$ $C_R(S)$ is the [[Consumer choice|choice set]] of $S$.

### Lemma
Every best element must be a maximal element, i.e. $C_R(S) \subset M_R(S)$.

## Kakutani's fixed point theorem
Let $X$ be a compact convex subset of $\mathbb{R}^n$ and let $f: X \rightarrow X$ be a set-valued function for which
+ for all $x \in X$ the set $f(x)$ is nonempty and convex
+ the graph of $f$ is closed (i.e. for all sequences $\{x_n\}$ and $\{y_n\}$ such that $y_n \in f(x_n)$ for all $n$, $x_n \rightarrow x$ and $y_n \rightarrow y$, we have $y \in f(x)$)
Then there exists an $x^* \in X$ such that $x^* \in f(x^*)$.

## Homoegenous function
Homoegenous of degree $\lambda$.
$$f(sx,sy) = s^\lambda f(x,y)$$
