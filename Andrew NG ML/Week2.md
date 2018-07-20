# Multivariate Linear Regression

$$
h_\theta = \left[
\begin{array}{cccc}
\theta_0 &
\theta_1 &
\cdots &
\theta_n &

\end{array}
\right]
$$



## Gradient Descent For Multiple Variables

$$
θ_j:=θ_j−α\frac1m\sum_{i=1}^m(h_θ(x^{(i)})−y^{(i)})⋅x^{(i)}_j\\
\sum_{i=1}^m(h_θ(x^{(i)})−y^{(i)})⋅x^{(i)}_j \Leftrightarrow \frac{\partial}{\partial \theta_j} J(\theta_0, \theta_1)
$$

## *feature scaling* and *mean normalization*

$$
x_i:=\frac{x_i-\mu_i}{s_i}
$$

Where $μ_i$ is the **average** of all the values for feature (i) and $s_i$ is the range of values (max - min), or $s_i$ is the standard deviation. 

- What's the difference between dividing deviation and dividing range? 

  