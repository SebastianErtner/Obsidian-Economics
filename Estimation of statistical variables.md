## Estimation methods
[[Statistical Estimation]]

## Possible properties of estimators
### Unbiasedness
Estimator $\hat\theta$ is called unbiased if $\mathbb{E}[\hat\theta] = \theta$

### Asymptotic unbiasedness
Estimator $\hat\theta$ is called asymptotically unbiased if $\lim_{n\rightarrow\infty}\mathbb{E}[\hat\theta] = \theta$

### Relative efficiency
Two unbiased estimators of parameter $\theta$ with [[Variance-covariance matrix|variance-covariance matrices]]. Estimator $\hat\theta$ is called relatively more efficient if:
$$V(\tilde\theta)-V(\hat\theta)$$
is [[Definite matrix|nonnegative definite]] (=positive semi-definite).

### Consistency
Estimator $\hat\theta_{(n)}$ is called consistent, if for any real number $\varepsilon > 0$:
$$\lim_{n\rightarrow\infty} P[|\hat\theta_{(n)}-\theta| > \varepsilon]  =0$$
In words: An estimator is consistent if the probability of observing a difference between the estimator and the real value that is bigger than a number $\varepsilon$ is zero if the number of observations approaches infinity.
Simpler: An estimator is consistent if its value approaches the real value if the number of observations approaches infinity.