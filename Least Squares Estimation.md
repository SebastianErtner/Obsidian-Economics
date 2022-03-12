## Linear regression model
For the linera regression model:
$$y_i = \sum_{j=1}^k x_{ij}\beta_j+\varepsilon_i ~~~\Leftrightarrow~~~ y = X\beta+\varepsilon$$
The least squares estimator is:
$$\hat\beta = (X'X)^{-1}X'y$$
By design, the OLS minimizes the sum of squared residuals:
$$\sum e_i^2 = \sum(y_i-X\hat\beta)^2$$

### Full ideal conditions (Gauss-Markov conditions)
i) Model is linear in parameter $\beta$
ii) $E(\varepsilon_i) = 0$
iii) $V(\varepsilon_i) = E(\varepsilon_i^2) = \sigma^2$
iv) $Cov(\varepsilon_i,\varepsilon_j) = E(\varepsilon_i,\varepsilon_j) = 0$
v) $X$ is determininstic with $rk(X) = k < n$

### Finite sample-properties
- i, ii and v imply unbiasedness of the OLS estimator
- i - v imply that the [[Variance-covariance matrix|variance-covariance matrix]] of the OLSE has the form: $\sigma^2(X'X)^{-1}$
- i - vd imply the [[Gauss-Markov theorem]]; OLS is BLUE