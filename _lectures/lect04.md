---
num: "lect04"
lecture_date: 2019-01-16
desc: "Matrix factorizations: LU, Cholesky, QR"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

Next Wednesday's lecture topics are not in the NCM book.
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
For Cholesky factorization, see
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/)
Problem 2.5 and
[Nick Higham's overview](http://www.maths.manchester.ac.uk/~higham/papers/high09c.pdf).

# Outline of today's lecture

More interesting kinds of matrices:

   - symmetric positive definite (SPD) matrices
   - (orthogonal matrices -- later!)
   - (sparse matrices -- later!)

Matrix factorizations:

   - A = PLU or A[p,:] = LU: LU factorization with partial pivoting of a square matrix
   - A = LL^T: Cholesky factorization of an SPD matrix
   - Lecture codes:
     - LUsolve()
   - numpy/scipy routines:
     - npla.solve()       [solve Ax = b using LU, dense]
     - linalg.lu()        [LU factorization]
     - linalg.cholesky()  [Cholesky factorization]
