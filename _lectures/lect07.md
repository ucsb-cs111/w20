---
num: "lect07"
lecture_date: 2020-01-28
desc: "Fitting data by least squares"
ready: true
---

* {% include lecture_files.html %}


# Reading assignment

For next Tuesday, read Section 2.9 (norms and condition numbers) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# References for today's lecture

Sections 5.1 through 5.5 of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# Outline

- More on the Jacobi and conjugate gradient methods
- Sparse matrices in numpy/scipy
- The factorization A = QR for non-square matrices A
- numpy/scipy routines:
  - scipy.sparse.csr_matrix()
  - scipy.sparse.linalg.spsolve()
  - scipy.sparse.linalg.cg()
  - spla.qr() [note: this is slightly different from npla.qr]
- Lecture codes:
  - Jsolve()
  - CGsolve()
