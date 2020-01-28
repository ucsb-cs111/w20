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

- More on the conjugate gradient method
- Manipulating sparse matrices in numpy/scipy
- numpy/scipy routines:
  - scipy.sparse.csr_matrix()
  - scipy.sparse.linalg.spsolve()
  - scipy.sparse.linalg.cg()
- Lecture codes:
  - Jsolve()
  - CGsolve()

- Data fitting by least squares using QR factorization
  - The factorization A = QR for non-square matrices A
  - Least squares problems: Ax $$\approx$$ b
    - a surveying problem
    - parametric curve fitting 
  - Solving Ax $$\approx$$ b by QR factorization

- numpy/scipy routines:
  - linalg.qr()
  - npla.lstsq() 
  - np.linspace() 
  - several matplotlib routines, see in-class transcript

