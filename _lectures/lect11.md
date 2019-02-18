---
num: "lect11"
lecture_date: 2019-02-20
desc: "Ordinary differential equations (ODEs)"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next week, continue reading NCM Chapter 7 through Section 7.5.
Section 7.5 is about an algorithm that 
Matlab calls BS23 (and implements as ode23tx);
this is the same algorithm that scipy calls RK23.

# References for today's lecture

NCM Sections 7.1 through 7.3 (ODEs).

# Outline

- Standard form of an ODE

- Software for solving ODEs numerically
  - integrate.solve_ivp()
  - examples of first-order ODEs
  - plotting solutions to ODEs
    - plt.plot()
    - plt.legend()
    - plt.xlabel(), plt.ylabel(), plt.title()

- Systems of ODEs
  - Lotka-Volterra equations
  - phase space plots

- ODEs with higher derivatives
  - the harmonic oscillator
