# Iterative Maps

## 1. Baker’s Map
$$
(x_{n+1}, y_{n+1}) =
\begin{cases}
(2x_n, \, a y_n), & 0 \leq x_n \leq \tfrac{1}{2}, \\ 
(2x_n - 1, \, a y_n + \tfrac{1}{2}), & \tfrac{1}{2} \leq x_n \leq 1
\end{cases}. \\ \qquad 0< a \le\tfrac{1}{2}
$$

## 2. Kaplan–Yorke Map
$$
\begin{aligned}
x_{n+1} &= 2x_n \pmod{1}, \\
y_{n+1} &= \alpha y_n + \cos(4\pi x_n),
\end{aligned}
\qquad 0<\alpha<1
$$

3D extension:

$$
\begin{aligned}
x_{n+1} &= \beta x_n \pmod{1}, \\
y_{n+1} &= \alpha y_n + \cos(4\pi x_n), \\
z_{n+1} &= \alpha z_n + \sin(4\pi x_n),
\end{aligned}
\qquad 0<\alpha<1
$$

## 3. Chirikov Standard Map
$$
\begin{aligned}
p_{n+1} &= p_n - K \sin q_n, \\
q_{n+1} &= q_n + p_{n+1} \pmod{2\pi}
\end{aligned}
$$


## 4. Quantum Map
$$
\begin{aligned}
x_{n+1} &= x_n + y_n, \\
y_{n+1} &= y_n - x_{n+1}^3
\end{aligned}
\qquad -1.13 < x,y < 1.13
$$


## 5. Hénon–Heiles Hamiltonian
$$
H = \frac{1}{2m}(p_x^2 + p_y^2) + \frac{1}{2}k(x^2+y^2) + \lambda(x^2 y - \tfrac{1}{3}y^3)
$$

In polar coordinates:
$$
H = \frac{p_r^2}{2m} + \frac{p_\theta^2}{2mr^2} + \tfrac{1}{2}kr^2 + \tfrac{1}{3}\lambda r^3 \sin(3\theta)
$$


## 6. Cubic Map (Hénon)
$$
\begin{aligned}
x_{n+1} &= x_n + a(y_n - y_n^3), \\
y_{n+1} &= y_n - a(x_{n+1} - x_{n+1}^3)
\end{aligned}
\qquad a=1.6
$$


## 7. Hénon’s Area-Preserving Quadratic Map
$$
\begin{aligned}
x_{n+1} &= x_n \cos\alpha - (y_n - x_n^2)\sin\alpha, \\
y_{n+1} &= x_n \sin\alpha + (y_n - x_n^2)\cos\alpha
\end{aligned}
\qquad 0 \leq \alpha \leq \pi
$$


## 8. Hénon Map
$$
\begin{aligned}
x_{n+1} &= 1 + y_n - a x_n^2, \\
y_{n+1} &= b x_n
\end{aligned}
$$


## 9. Lozi Map
$$
\begin{aligned}
x_{n+1} &= 1 + y_n - a |x_n|, \\
y_{n+1} &= b x_n
\end{aligned}
$$


## 10. Ikeda Map
$$
\begin{aligned}
x_{n+1} &= 1 + u\,(x_n \cos\theta_n - y_n \sin\theta_n), \\
y_{n+1} &= u\,(x_n \sin\theta_n + y_n \cos\theta_n), \\
\theta_n &= c - \frac{d}{1+x_n^2+y_n^2}
\end{aligned}
$$


## 11. Modified Hénon’s Map
$$
\begin{aligned}
x_{n+1} &= 1 + \beta x_n - \alpha y_n^2, \\
y_{n+1} &= x_n
\end{aligned}
$$


## 12. Web Map (Periodically-Kicked Hamiltonian System)
Equation of motion:
$$
\ddot{x} + \omega_0^2 x = -\omega_0 K \sin x \sum_{n=-\infty}^{\infty} \delta(t-nT)
$$

Equivalent discrete web map:
$$
\begin{aligned}
x_{n+1} &= x_n + y_{n+1}, \\
y_{n+1} &= y_n - K \sin(x_n)
\end{aligned}
$$
