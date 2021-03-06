---
num: "lect04"
lecture_date: 2020-01-16
desc: "LU factorization: error, residual, complexity, partial pivoting"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

Next Tuesday's lecture topics are not in the NCM book.
Instead, please read two sections of the
[Templates book](http://www.netlib.org/linalg/html_templates/report.html):
one on the
[Jacobi method](http://www.netlib.org/linalg/html_templates/node12.html)
and one on the
[conjugate gradient method (CG)](http://www.netlib.org/linalg/html_templates/node20.html).

If you're interested in learning more about how CG works,
there's a great paper called
[An introduction to the conjugate gradient method without the agonizing pain](https://people.eecs.berkeley.edu/~jrs/jrspapers.html#cg) by Jonathan Shewchuk at Berkeley.
Reading it is optional for CS 111, but fun if you like the math.


# References for today's lecture

[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/)
Sections 2.1 through 2.6 (linear equations and Gaussian elimination),
Sections 2.8 (error and residual).


# Outline

- This week's big idea: Matrix Factorizations

- More on solving Ax = b by Gaussian elimination:
  - Residual b - Ax, residual norm
  - Details of lower triangular solve
  - Complexity analysis of LU factorization and triangular solve
  - LU factorization with partial pivoting
  - Permutation vectors and permutation matrices

- Interesting matrices:
  - Permutation matrices

- numpy/scipy routines:
  - npla.norm()
  - npla.solve()
  - spla.lu()

- Lecture codes:
  - LUfactor()
  - Lsolve()
  - Usolve()
  - LUsolve()

