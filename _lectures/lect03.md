---
num: "lect03"
lecture_date: 2019-01-14
desc: "Solving Ax=b by LU factorization"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

Wednesday's lecture topics are not in the NCM book.
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
Sections 2.1 through 2.6 (linear equations and Gaussian elimination).

# Outline of today's lecture

More interesting kinds of matrices:

   - triangular matrices
   - unit triangular matrices

Solving Ax = b:

   - Residual b - Ax, residual norm
   - Solving triangular systems
   - Gaussian elimination and LU factorization
   - Partial pivoting
   - Lecture codes:
     - LUfactor() 
     - Lsolve() 
     - Usolve()
   - numpy/scipy routines:
     - npla.matrix_rank()
     - npla.norm()
     - npla.cond()
     - npla.solve()
     - linalg.lu()
