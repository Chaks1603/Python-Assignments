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

  2D extension: 

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

## 3. Standard Map

i.

$$
\begin{aligned} 
x_{n+1} &= x_n+y_{n+1}, \\
y_{n+1} &= y_n+k\sin x_n
\end{aligned}
$$                                            

ii.

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

## 12. Zaslavskii Map

$$ 
\begin{aligned}
x_{n{\tiny + 1}} &= [x_n + \nu(1 + \mu y_n) + \epsilon\nu\mu\cos(2\pi x_n)]\mod 1 \\                                                       
y_{n{\tiny + 1}} &= e^{-\Gamma} (y_n + \epsilon\cos(2\pi x_n)) \\                                  
\mu &= \frac{1 - e^{-\Gamma}}{\Gamma}
\end{aligned}
$$


## 13. Web Map (Periodically-Kicked Hamiltonian System)

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


# Patterns 

## 1. Cantor Set

## 2. Lévy C-Curve

## 3. Pythagoras Tree

### i. Perfect

### ii. Imperfect

## 4. Barnsley's Fern Fractal

### i. Case 1
$$
(x_{n+1}, y_{n+1}) =
\begin{cases}
(0.5, 0.27y_n), & r < 0.02,\\
(−0.139x_n + 0.263y_n + 0.57, \\
0.246x_n + 0.224y_n − 0.036), & 0.02 \le r \le 0.17,\\
(0.17x_n − 0.215y_n + 0.408, \\
0.222x_n + 0.176y_n + 0.0893), & 0.17 < r \le 0.3,\\
(0.781x_n + 0.034y_n + 0.1075,\\
−0.032x_n + 0.739y_n + 0.27), & 0.3 < r < 1.
\end{cases}.  
$$

### ii. Case 2
$$
(x,y)_{n+1} = 
\begin{cases}
(0, 0.16y_n), & r < 0.01,\\    
(0.85x_n + 0.04y_n, \\                                
-0.04x_n + 0.85y_n + 1.6), & 0.01 \le r < 0.86,\\    
(0.2x_n - 0.26y_n, \\                            
0.23x_n + 0.22y_n + 1.6), & 0.86 \le r < 0.93,\\  
(-0.15x_n + 0.28y_n,\\                           
0.26x_n + 0.24y_n + 0.44), & 0.93 \le r < 1.
\end{cases}  
$$ 

### ii. Case 3
$$
(x,y)_{n+1} =
\begin{cases}
(0, 0.25y_n - 0.4), & r < 0.02,\\ 
(0.95x_n + 0.005y_n - 0.002, \\ 
-0.005x_n + 0.93y_n + 0.5), & 0.02 \le r < 0.86,\\ 
(0.035x_n - 0.2y_n - 0.09, \\ 
0.16x_n + 0.04y_n + 0.02), & 0.86 \le r < 0.93,\\ 
(-0.04x_n + 0.2y_n + 0.083,\\ 
0.16x_n + 0.04y_n + 0.12), & 0.93 \le r < 1.
\end{cases}
$$ 

### iv. Self-Affin Tree
$$
(x,y)_{n+1} = 
\begin{cases}
(0.05x_n, 0.6y_n), & 10 \\% , \\ 
(0.05x_n, \\
−0.5y_n + 1.0),& 10 \\% ,\\
(0.46x_n − 0.15y_n,\\ 
0.39x_n + 0.38y_n + 0.6), & 20 \\% ,\\
(0.47x_n − 0.15y_n,\\ 
0.17x_n + 0.42y_n + 1.1), & 20 \\% ,\\ 
(0.43x_n + 0.28y_n,\\ 
−0.25x_n + 0.45y_n + 1.0), & 20 \\% ,\\
(0.42x_n + 0.26y_n, \\
−0.35x_n + 0.31y_n + 0.7), & 20 \\%.
\end{cases}
$$

## 5. Sierpiński Case

### i. Gasket or Sierpinski triangles pattern.
### ii. Carpet
### iii. Cantor Dust 
### iv. Vicsek fractal or Vicsek Snowflake
### v. cross form of the Vicsek fractal
### vi. cross-shaped Cantor square or rotated Cantor dust.
### vii. Pyramid
### viii. Cube
### ix. Jeruselum Cross
### ix. Jeruselum Cube
### x. Cheese

## 6. Koch 

### i. Curve

### ii. Snowflakes

## 7. Curve

### i. Mystery Curve
Distributing the global rotation term $e^{it}$ gives:  

$$f(t) = e^{it} - \frac{1}{2}e^{i(k+1)t} + \frac{i}{3}e^{-i(k-1)t}$$ 

Converting this into standalone $x(t)$ and $y(t)$ coordinates yields:

$$\begin{aligned}
x(t) &= \cos(t) - \frac{1}{2}\cos\big((k+1)t\big) + \frac{1}{3}\sin\big((1-k)t\big) \\
y(t) &= \sin(t) - \frac{1}{2}\sin\big((k+1)t\big) + \frac{1}{3}\cos\big((1-k)t\big) 
\end{aligned}$$

### ii. Moore Curve
#### Formal Definition

* **Alphabet:** $\Sigma = \{L, R\}$
* **Constants:** $C = \{F, +, -\}$
* **Axiom $(\omega)$:**   $\omega = LFL+F+LFL$

#### Production Rules

The generation rules applied concurrently to every structural element at each recursive iteration are:

$$\begin{aligned}
L &\longrightarrow -RF+LFL+FR- \\
R &\longrightarrow +LF-RFR-FL+
\end{aligned}$$

#### Command Interpretations

When parsing the final string into geometric coordinate steps:
* $F$ : Draw forward one unit step length
* $-$ : Turn left by $90^\circ$ (counter-clockwise)
* $+$ : Turn right by $90^\circ$ (clockwise)

### iii. Hilbert Curve
The length $L_n$ of the $n$-th curve is defined as

$$ L_n = 2^n - \frac{1}{2^n}$$


### iv. Gosper Curve

#### Formal Definition

* **Angle $(\theta)$:** $60^\circ$
* **Axiom $(\omega)$:**  $\omega = A$

#### Production Rules

The replacement rules applied concurrently to every variable at each recursive iteration are:

$$\begin{aligned}
A &\longrightarrow A - B - - B + A + + A A + B - \\
B &\longrightarrow + A - B B - - B - A + + A + B
\end{aligned}$$

#### Command Interpretations

When parsing the final generated string array using a "turtle-style" graphics processor:
* **$A$ or $B$** : Move forward drawing a straight line segment
* **$-$** : Turn left by $60^\circ$ (clockwise)
* **$+$** : Turn right by $60^\circ$ (counter-clockwise)

## 8. Diffusion-Limited Aggregation(DLA)

## 9. Correlated Ballistic Deposition

## 10. Weierstrass Function
