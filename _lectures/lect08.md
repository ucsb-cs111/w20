---
num: "lect08"
lecture_date: 2020-02-04
desc: "Data fitting by least squares with QR factorization"
ready: true
---

* {% include lecture_files.html %}


# Reading assignment

For Thursday, read Section 2.9 (norms and condition numbers) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# References for today's lecture

Sections 5.1 through 5.5 of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# Outline

- Manipulating sparse matrices in numpy/scipy

- Data fitting by least squares using QR factorization
  - The factorization A = QR for non-square matrices A
  - Least squares problems: Ax $$\approx$$ b
    - a surveying problem
  - Solving Ax $$\approx$$ b by QR factorization

- numpy/scipy routines:
  - scipy.sparse.csr_matrix()
  - spla.qr() [note: this is slightly different from npla.qr]
  - npla.lstsq() 


