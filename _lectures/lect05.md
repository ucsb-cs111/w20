---
num: "lect05"
lecture_date: 2020-01-21
desc: "Permutation vectors and matrices, SPD matrices, Cholesky"
ready: true
---

* {% include lecture_files.html %}


# Reading assignment

Thursday's lecture topics are not in the NCM book.
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
Problem 2.5 (Cholesky factorization) and
Section 5.5 (QR factorization).

# Outline

- More on matrix factorizations:
  - Using LU factorization with partial pivoting to solve Ax = b
  - Permutation matrices and permutation vectors
  - SPD matrices, Cholesky factorization, and Ax = b
  - Orthogonal matrices, QR factorization, and Ax = b

- Interesting matrices:
  - Permutation matrices
  - Symmetric positive definite (SPD) matrices
  - Orthogonal matrices

- numpy/scipy routines:
  - npla.norm()
  - npla.solve()
  - spla.lu()
  - npla.cholesky()
  - npla.qr()

- Lecture codes:
  - LUfactor()
  - Lsolve()
  - Usolve()
  - LUsolve()
