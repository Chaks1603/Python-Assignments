# Damped Driven Pendulum's Oscillation Equation

The equation of motion is just $I\ddot{\theta} = \Gamma$, where $I$ is the moment of inertia and $\Gamma$ is the net torque about the pivot.                                                                                                                     
In this case $I = m L^2 ,$ and the torque arises from the three forces shown in Figure below.    

![Driven-damped-pendulum](https://raw.githubusercontent.com/Chaks1603/Storage/main/Driven-damped-pendulum.png)

The resistive force has magnitude  $bv$  and hence exerts a torque $-Lbv = -bL^2\dot{\theta}$.

The torque of the weight is $-mgL\sin\theta,$ and that of the driving force is $LF(t)$. 

Thus, the equation of motion $I\ddot{\theta}=\Gamma$ is :

$\qquad mL^2\ddot{\theta} = -bL^2\dot{\theta} - mgL\sin\theta + LF(t) \qquad\qquad\qquad ({1})$

Assume that the driving force $F(t)$ is sinusoidal:

$\qquad F(t) = F_o\cos(\omega t) \qquad\qquad\qquad\qquad\qquad\qquad\qquad({2})$

where $F_o$ is the drive amplitude (the amplitude of the driving force) and $\omega$ is the drive frequency. 

Substituting $(2)$ into $(1),$ we find:

$\therefore \quad mL^2\ddot{\theta} = -bL^2\dot{\theta} - mgL\sin\theta + LF_o\cos(\omega t) \qquad\qquad({3})$

or, $\quad\ddot{\theta} + \frac{b}{m} \dot{\theta} + \frac{g}{L} \sin\theta = \frac{F_0}{mL} \cos \omega t$

Finally,

$\qquad\ddot{\theta} + 2\beta\dot{\theta} + \omega^2_o\sin{\theta} = \gamma\omega^2_o\cos\omega t \qquad\qquad\qquad\qquad({4})$

where:
- Damping constant $= \beta ,$
- Natural frequency $= \omega_o ,$
- Driving strength $= \gamma$ (dimensionless).
