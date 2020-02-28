---
num: "lect16"
lecture_date: 2020-03-03
desc: "ODEs: stiff problems"
ready: false
---

* {% include lecture_files.html %}

# Reading assignment

Work on the sample midterm problems!


# References for today's lecture

Read NCM Section 7.9 (stiff ODEs) and
[this page](http://web.mit.edu/10.001/Web/Course_Notes/Differential_Equations_Notes/node3.html) on forward and backward Euler 
(you just need the methods, not the convergence analysis).

# Outline

- Local error, global error, and stability 

- Stiff ODEs
  - Symptoms and effects of stiffness 
  - Example: the flame ODE
  - Example: the valley walk ODE
  - Motivation for implicit methods
  - The backward Euler method
  - Issues in implicit methods
  - The Radau implicit method in scipy
