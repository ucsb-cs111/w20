---
num: "lect07"
lecture_date: 2019-01-30
desc: "Least squares; matrix condition number and norm"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next Monday, read Section 1.7 (floating-point arithmetic) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book, 
and look at this [Wikipedia page](https://en.wikipedia.org/wiki/Double-precision_floating-point_format) on floating-point format.

# References for today's lecture

Section 2.9 (norms and condition numbers) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# Outline

Finishing up QR and least squares:
   - Solving Ax $$\approx$$ b by QR factorization
   - Parametric curve fitting

Norm and condition number:
   - Norm of a vector: l_2 (Euclidean) norm and others
   - Condition number of a matrix [next time]
   - Sensitivity analysis of Ax = b [next time]
   - Norm of a matrix [next time]

numpy/scipy routines:
   - linalg.qr()
   - npla.lstsq()
   - np.linspace()
   - npla.norm() [next time]
   - npla.cond() [next time]

several matplotlib routines, see in-class transcript
