---
num: "lect14"
lecture_date: 2020-02-25
desc: "Ordinary differential equations (ODEs)"
ready: false
---

* {% include lecture_files.html %}

# Reading assignment

For Thursday, continue reading NCM Chapter 7 through Section 7.5.
Section 7.5 is about an algorithm that 
Matlab calls BS23 (and implements as ode23tx);
this is the same algorithm that scipy calls RK23.

# References for today's lecture

NCM Sections 7.1 through 7.3 (ODEs).

# Outline

- Standard form of an ODE
- Examples of first-order ODEs
- Systems of ODEs
  - Lotka-Volterra equations
  - phase space plots

- numpy/scipy routines:
  - integrate.solve_ivp()
  - plt.plot()
  - plt.xlabel(), plt.ylabel(), plt.title()
  - plt.legend()

- cs111 routines:
  - cs111.ode1()
  - cs111.ode2()
