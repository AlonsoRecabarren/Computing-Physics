# Dynamics of a Two-Level Open Quantum System

Semester Project - Computing Physics

## Description

This project studies the dynamics of a two-level quantum system interacting with a coherent laser field and an external dissipative environment.

The evolution of the system is modeled through the Lindblad Master Equation, allowing the inclusion of spontaneous emission and decoherence processes.

The main goals of the project are:

- Compare different numerical integration methods.
- Validate numerical solutions against known analytical results.
- Study the effects of dissipation and detuning on the system dynamics.
- Obtain the absorption spectrum of the atom through frequency sweeps.
  
## Physical Model

The system considered is a two-level atom driven by a monochromatic laser field.

The Hamiltonian in the rotating frame is

$$
H = -\frac{\delta}{2}\sigma_z + \frac{\Omega}{2}\sigma_x
$$

where:

- $\Omega$ is the Rabi frequency.
- $\delta = \omega - \omega_0$ is the detuning.
- $\omega_0$ is the atomic transition frequency.
- $\omega$ is the laser frequency.

Dissipation is introduced through the Lindblad master equation

$$
\frac{d\rho}{dt}=
-i[H,\rho]+
\sum_i \gamma_i \cdot
\left(
L_i \rho L_i^\dagger-
\frac{1}{2}
\{L_i^\dagger L_i,\rho\}
\right)
$$

with spontaneous emission represented by

$$
L = \sigma_-.
$$

## Author

Alonso Recabarren

Undergraduate Physics Program

Universidad Técnica Federico Santa María

2026
