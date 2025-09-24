# Iterative Maps 


## 1. Sine Map
$$
x_{n+1} = f(x_n), \quad f(x) = r \sin(\pi x)
$$


## 2. Logistic Map
$$
x_{n+1} = r x_n (1 - x_n)
$$


## 3. Gaussian Map
$$
x_{n+1} = e^{-b x_n^2} + c
$$


## 4. Exponential Map (Variant A)
$$
x_{n+1} = x_n e^{-r(1-x_n)}
$$


## 5. Exponential Map (Variant B)
$$
x_{n+1} = e^{-r x_n}
$$


## 6. Cosine Map
$$
x_{n+1} = r \cos(x_n)
$$


## 7. Tent Map
$$
x_{n+1} =
\begin{cases}
r x_n, & x_n \leq \tfrac{1}{2}, \\
r (1 - x_n), & x_n > \tfrac{1}{2}
\end{cases}
$$


## 8. Tangent Map
$$
x_{n+1} = r \tan(x_n)
$$


## 9. Cubic Map
$$
x_{n+1} = r x_n - x_n^3
$$


## 10. Quadratic Map
$$
x_{n+1} = C - x_n^2
$$


## 11. Square-Root Map
$$
x_{n+1} = \sqrt{x_n}
$$


## 12. Circle Map
$$
\theta_{n+1} = \theta_n + \Omega - \frac{K}{2\pi}\sin \big(2\pi \theta_n\big),
\qquad \theta_n > 0
$$


## 13. Sine-Circle Map
$$
\theta_{n+1} = \theta_n + \Omega - \frac{K}{2\pi}\sin(2\pi \theta_n) \pmod{1},
\qquad 0.5 < K < 5.5 ,\ \Omega=0.5
$$


## 14. Devil’s Staircase (Cantor Function)

Probability distribution:

$$
P(x) = \mathbb{P}(\text{random point in Cantor set } \leq x), 
\qquad 0 \leq x \leq 1
$$

Constructed via iterative approximations:

$$
P_0(x) = x, \quad P_n(x) \to P_\infty(x) \ \ (\text{Devil’s Staircase})
$$

