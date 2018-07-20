# Linear Regression 1 variable (Supervised)

Consisting of two parts. First is the cost function for us to minimize. Second is the Gradient Descent algorithm to minimize it.

## Cost Function

$$
J(\theta_0,\theta_1)=\frac{1}{2m}\sum_{i=1}^m(h_\theta(x_i)-y_i)^2
$$

## Gradient Descent (Parameter Learning)

repeat until convergence:
$$
\theta_j := \theta_j - \alpha \frac{\partial}{\partial \theta_j} J(\theta_0, \theta_1)
$$
where $j$ represents 0, 1
$$
\begin{align*}
&temp0= \theta_0 - \alpha \frac{\partial}{\partial \theta_0} J(\theta_0, \theta_1)\\
&temp1= \theta_1 - \alpha \frac{\partial}{\partial \theta_1} J(\theta_0, \theta_1)\\
&\theta_0=temp0\\
&\theta_1=temp1\\
\end{align*}
$$

- Why using partial not gradient？
  - (Page88 in Calculus book) Because gradient is the same with partial derivatives times sin cos.