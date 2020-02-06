---
num: "lect09"
lecture_date: 2020-02-06
desc: "Norms of vector and matrices, matrix condition number"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next Tuesday, read
Section 1.7 (floating-point arithmetic) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book, 
and this [Wikipedia page](https://en.wikipedia.org/wiki/Double-precision_floating-point_format) on floating-point format.

You may also want to look at this
[nice article on the IEEE 64-bit floating-point standard](https://www.johndcook.com/blog/2009/04/06/anatomy-of-a-floating-point-number/)
by John Cook.
Also, [here](https://www.nextplatform.com/2018/05/10/tearing-apart-googles-tpu-3-0-ai-coprocessor/) is an interesting article on Google's TPU processor, which uses a different floating-point format.


# References for today's lecture

Sections 5.1 (curve fitting), 
2.8 (effect of roundoff errors),
and 2.9 (norms and condition numbers) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# Outline

- Data fitting by least squares using QR factorization
    - Parametric curve fitting 

- Norm and condition number
   - Norm of a vector: l_2 (Euclidean) norm and others
   - Norm of a matrix 
   - Condition number of a matrix 
   - Sensitivity analysis of Ax = b 

- numpy/scipy routines:
  - npla.lstsq() 
  - np.linspace() 
  - several matplotlib routines, see in-class transcript
  - npla.norm()
  - npla.cond()

