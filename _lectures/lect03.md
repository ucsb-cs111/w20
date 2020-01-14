---
num: "lect03"
lecture_date: 2020-01-14
desc: "Solving Ax=b by LU factorization"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment for next lecture

Read [NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/)
Problem 2.5 (Cholesky factorization) 
and Section 5.5 (QR factorization)

# References for today's lecture

[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/)
Sections 2.1 through 2.6 (linear equations and Gaussian elimination).


# Outline

- This week's big idea: Matrix Factorizations

- Interesting matrices:
  - Triangular matrices
  - Unit triangular matrices

- Solving Ax = b by LU factorization:
  - Residual b - Ax, residual norm
  - Solving triangular systems
  - Gaussian elimination
  - LU factorization
  - Partial pivoting

- numpy/scipy routines:
  - npla.matrix_rank()
  - npla.norm()
  - npla.cond()
  - npla.solve()
  - linalg.lu()

- Lecture codes:
  - LUfactor()
  - Lsolve()
  - Usolve()

