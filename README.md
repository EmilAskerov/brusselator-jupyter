# Brusselator jupyter
The system is described by the classic Brusselator equations:

dx/dt=A - (B + 1) * x + x^2 * y

dy/dt=Bx - x^2 * y

The analytical study of the system's stability has been performed.

A > 0

B = 9 * (A - 1)

All possible types of equilibrium (stationary) points have been identified for the specified functional dependence B=f(A).

The boundaries demarcating these types of equilibrium points have been determined, along with the corresponding ranges for parameter A.

The model has been numerically implemented using the fourth-order Runge-Kutta method.

The simulation results can be visualized both as time series plots of x(t) and y(t), and as a phase portrait (y vs. x).

For trajectories evolving towards or near stable equilibrium points, the initial conditions were set to x₀ = A + 5, y₀ = B/A.

For trajectories originating near unstable equilibrium points, the initial conditions were x₀ = A + 0.005, y₀ = B/A.


Furthermore, scenarios (visualized as phase portraits) have been pre-established to illustrate the transitions between different types of equilibrium points as parameter A is varied.


Tested using VSCode and Python 3.13.3.
