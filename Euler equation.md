


Growth model:

[[Lifetime discounted utility]]:
$$U(\{c_t\}) = \sum_{t = 0}^\infty \beta^t u(c_t)$$
Capital Accumulation
$$k_{t+1}+c_t = f(k_t)+(1-\delta)k_t$$
Lagrange:
$$\mathcal{L}(c_t,k_{t+1}) = \sum_{t = 0}^\infty \beta^t u(c_t)+\lambda_t[k_{t+1}+c_t-f(k_t)-(1-\delta)k_t]$$
FONCs:

$$\frac{\partial \mathcal{L}}{\partial c_t} = \beta^tu'(c_t)+\lambda_t$$
$$\frac{\partial \mathcal{L}}{\partial k_{t+1}} = \lambda_t+\lambda_{t+1}[-f'(k_{t+1})-(1-\delta)]$$

The Euler equation is the result of combining both FONCs:

$$1 = \frac{\beta u'(c_{t+1})}{u'(c_t)}[f'(k_{t+1})+(1-\delta)]$$