# Linear Algebra
1. Gauss Elimination
2. Gauss Elimination with Backsubstitution
3. Gauss Elimination with Backsubstitution and Pivot
4. Gauss-Jordan Elimination
5. Gauss Seidel iterative method
6. Jacobi iterative method
7. Cholesky Decomposition
8. LU Decomposition
9. QR Decomposition
10. Power Iteration and Inverse Power Iteration

# Special Polynomial Functions
1.	Legendre Function : $\displaystyle(1-x^2)\ddot{y} -2x\dot{y} + n(n+1)y = 0$
2.	Chebyshev Function : $\displaystyle(1-x^2)\ddot{y}-x\dot{y}+n^2y=0  $
3.	Hermite Function : $\displaystyle\ddot{y} - 2x\dot{y} + 2ny = 0 $
4.	Laguerre Function : $\displaystyle x\ddot{y} + (1 - x)\dot{y} + n y = 0 $
5.	Bessel Function : $\displaystyle x^2 \ddot{y} + x \dot{y} + (x^2 - n^2) y = 0 $
6.	Hyper-Geometric Function : $\displaystyle x(1-x)\ddot{y}+[c-(a+b+1)x]\dot{y}-aby=0$
7.	Confluent Hyper-Geometric Function : $\displaystyle x \ddot{y} + (b-x) \dot{y} - ay = 0 $
8.	Gamma Function :
9.	Beta Function :
10.	Error Function :

# Integrations
1. Trapezoidal method
2. Simpson method
3. Newton Cotes
4. Gauss Quadratures
5. Euler's Forward & Backward method
7. Runge-Kutta method
8. Leap-Frog method
9. Predictor-Corrector method
10. Adams-Bashforth Method
11. Adams-Moulton Method

# Partial Differential Equations
1. Diffusion Equation : $\displaystyle{\frac{\partial \phi}{\partial t} = \kappa \nabla^2 u} $
2. Wave Equation : $\displaystyle \frac{\partial u}{\partial t}=-c\nabla u$
3. Burgers Equation : $\displaystyle\frac{\partial u}{\partial t}=-u\nabla u+\nu\nabla^2 u$
4.  KPZ Equation : $\displaystyle\frac{\partial u}{\partial t}=\frac{1}{2}(\nabla u)^2+\nu\nabla^2 u$
5.  KDV Equation : $\displaystyle\frac{\partial u}{\partial t}=-u\nabla u+\nu\nabla^3 u$
6. Navier-Stokes Equation : $\displaystyle \frac{\partial \mathbf{u}}{\partial t}+\mathbf{u}\cdot\nabla \mathbf{u}=-\frac{1}{\rho}\nabla p+\nu\nabla^2 \mathbf{u} \ , \quad \nabla\cdot\mathbf{u}=0  \ ,\quad \nabla^2 p=-\rho\nabla\cdot\bigg[\mathbf{u}\cdot\nabla\mathbf{u}\bigg]$
7. Schrodinger Equation : $\displaystyle{i\hbar\frac{\partial\psi}{\partial t}=−\frac{\hbar^2}{2m}\nabla\psi+V\psi}$ 

where $\displaystyle{\nabla=\hat{i}\frac{\partial}{\partial x}+\hat{j}\frac{\partial}{\partial y}+\hat{k}\frac{\partial}{\partial z}}$

# Damped Driven Pendulum's Oscillation Equation

The equation of motion is just $I\ddot{\theta} = \Gamma$, where $I$ is the moment of inertia and $\Gamma$ is the net torque about the pivot.                                                                                                                     
In this case $I = m L^2 ,$ and the torque arises from the three forces shown in Figure .    

![Driven-damped-pendulum](https://raw.githubusercontent.com/Chaks1603/Storage/main/Driven-damped-pendulum.png)

The resistive force has magnitude  $bv$  and hence exerts a torque $-Lbv = -bL^2\dot{\theta}$.

The torque of the weight is $-mgL\sin\theta,$ and that of the driving force is $LF(t)$. 

Thus, the equation of motion $I\ddot{\theta}=\Gamma$ is :

$\qquad mL^2\ddot{\theta} = -bL^2\dot{\theta} - mgL\sin\theta + LF(t) \tag{1}$

Assume that the driving force $F(t)$ is sinusoidal:

$\qquad F(t) = F_o\cos(\omega t) \tag{2}$

where $F_o$ is the drive amplitude (the amplitude of the driving force) and $\omega$ is the drive frequency. 

Substituting $(2)$ into $(1),$ we find:

$\therefore \quad mL^2\ddot{\theta} = -bL^2\dot{\theta} - mgL\sin\theta + LF_o\cos(\omega t) \tag{3}$

or, $\qquad\ddot{\theta} + \frac{b}{m}\dot{\theta} + \frac{g}{L}\sin\theta = \frac{F_o}{mL}\cos\omega t \quad \left[ \because \ \frac{b}{m}=2\beta,\frac{g}{L}=\omega_o^2, \gamma=\frac{F_o}{mL\omega_o^2}=\frac{F_o}{mg} \right]$

Finally,

$\qquad\ddot{\theta} + 2\beta\dot{\theta} + \omega^2_o\sin{\theta} = \gamma\omega^2_o\cos\omega t \tag{4}$

where:
- Damping constant $= \beta ,$
- Natural frequency $= \omega_o ,$
- Driving strength $= \gamma$ (dimensionless).
