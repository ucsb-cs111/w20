---
num: "lect06"
lecture_date: 2019-01-28
desc: "QR factorization and fitting data by least squares"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For Wednesday, read Section 2.9 (norms and condition numbers) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# References for today's lecture

Sections 5.1, 5.2, and 5.5 of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# Outline

Interesting matrices:

   - Orthogonal matrices

QR and least squares:

   - The factorization A = QR for square matrices A
   - Solving Ax = b by QR factorization
   - The factorization A = QR for non-square matrices A
   - Least squares problems: Ax $$\approx$$ b
     - a surveying problem
     - parametric curve fitting [next time]
   - Solving Ax $$\approx$$ b by QR factorization [next time]

numpy/scipy routines:
   - linalg.qr()
   - np.eye()
   - npla.lstsq() [next time]
   - np.linspace() [next time]
