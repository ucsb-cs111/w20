---
num: "lect06"
lecture_date: 2020-01-23
desc: "Solving Ax = b by Jacobi and conjugate gradients"
ready: true
---

* {% include lecture_files.html %}


# Reading assignment

Sections 5.1 through 5.5 of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# References for today's lecture

Today's lecture topics are not in the NCM book.
Here are references for the
[Jacobi method](http://www.netlib.org/linalg/html_templates/node12.html)
and the
[conjugate gradient method (CG)](http://www.netlib.org/linalg/html_templates/node20.html).

If you're interested in learning more about how CG works,
there's a great paper called
[An introduction to the conjugate gradient method without the agonizing pain](https://people.eecs.berkeley.edu/~jrs/jrspapers.html#cg) by Jonathan Shewchuk at Berkeley.
Reading it is optional for CS 111, but fun if you like the math.

# Outline

- Iterative methods for solving Ax = b:
  - Jacobi method 
  - Conjugate gradient method
- Manipulating sparse matrices in numpy/scipy
- Interesting matrices:
  - Sparse matrices
  - Symmetric positive definite (SPD) matrices, again
- numpy/scipy routines:
  - scipy.sparse.csr_matrix()
  - scipy.sparse.linalg.spsolve()
  - scipy.sparse.linalg.cg()
  - np.diag()
  - A.diag() [for any array A]
- Lecture codes:
  - Jsolve()
  - CGsolve()
