---
num: "lect15"
lecture_date: 2020-03-03
desc: "ODEs: algorithms"
ready: false
---

* {% include lecture_files.html %}

# Reading assignment

Read NCM Section 7.9 (stiff ODEs)

# References for today's lecture

NCM Chapter 7 through Section 7.5.
Section 7.5 is about an algorithm that 
Matlab calls BS23 (and implements as ode23tx);
this is the same algorithm that scipy calls RK23.

# Outline

- ODEs with higher derivatives
  - the harmonic oscillator

- Euler's method (the forward Euler algorithm)
- Variants of Euler's method
- The RK23/BS23 algorithm and its relatives

- cs111 routines:
  - cs111.ode1()
  - cs111.ode2()
