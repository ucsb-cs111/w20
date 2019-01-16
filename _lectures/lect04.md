---
num: "lect04"
lecture_date: 2019-01-16
desc: "Solving Ax=b by Jacobi and conjugate gradient"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next Wednesday, read sections x-y of the NCM book.

# References for today's lecture

The sections on the
[Jacobi method](http://www.netlib.org/linalg/html_templates/node12.html)
and the
[conjugate gradient method (CG)](http://www.netlib.org/linalg/html_templates/node20.html)
from the
[Templates book](http://www.netlib.org/linalg/html_templates/report.html).

If you're interested in learning more about how CG works,
there's a great paper called
[An introduction to the conjugate gradient method without the agonizing pain](https://people.eecs.berkeley.edu/~jrs/jrspapers.html#cg) by Jonathan Shewchuk at Berkeley.
Reading it is optional for CS 111, but it's fun if you like the math.

# Outline of today's lecture

More interesting kinds of matrices:

   - symmetric positive definite (SPD) matrices

Solving Ax = b:

   - Finishing off LU factorization with partial pivoting
   - numpy/scipy routines:
     - linalg.lu()
   - Iterative methods for Ax = b part 1: Jacobi iteration 
   - Iterative methods for Ax = b part 2: Conjugate gradients
   - Lecture codes:
     - CGsolve()
   - numpy/scipy routines:
     - ...
