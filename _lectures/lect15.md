---
num: "lect15"
lecture_date: 2020-02-27
desc: "ODEs: algorithms"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

Read NCM Section 7.9 (stiff ODEs) and
[this page](http://web.mit.edu/10.001/Web/Course_Notes/Differential_Equations_Notes/node3.html) on forward and backward Euler 
(you just need the methods, not the convergence analysis).

# References for today's lecture

NCM Chapter 7 through Section 7.5.
Section 7.5 is about an algorithm that 
Matlab calls BS23 (and implements as ode23tx);
this is the same algorithm that scipy calls RK23.

# Outline

- ODEs with higher derivatives
  - the harmonic oscillator

- Euler's method (the forward Euler algorithm)
- 2-slope variants of Euler's method
- The RK23/BS23 algorithm and its relatives

- cs111 routines:
  - cs111.ode1()
  - cs111.ode2()
