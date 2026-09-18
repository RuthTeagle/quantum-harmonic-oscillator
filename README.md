# Quantum Harmonic Oscillator Simulation
Numerical approximation of TISE and TDSE for quantum harmonic oscillator, extending to Gaussian wavepacket evolution. Error analysis of finite differences method and domain width used. 

## Project overview
This project involves finding solutions of the time-independent Schrodinger Equations for a 1D harmonic potential using the central difference method, from the family of finite difference methods. The absolute error in the numerically determined $E_n$ (compared to the analytical $E_n$) is considered. This permits analysis of errors including 
- Roundoff error
- Truncation error
- Error due to the chosen domain width
This error analysis justifies the chosen parameter values dx, L and N.

Next, a Gaussian wavepacket at the equilibrium position with non-zero initial momentum is constructed by superposing the numerically determined eigenstates. The time-dependent wavepacket dynamics are considered, and the wavepacket is identified as a 'squeezed state' of the QHO. 

