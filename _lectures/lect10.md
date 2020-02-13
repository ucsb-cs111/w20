---
num: "lect10"
lecture_date: 2020-02-11
desc: "Norms of vector and matrices, matrix condition number"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For Thursday, read
Section 1.7 (floating-point arithmetic) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book, 
and this [Wikipedia page](https://en.wikipedia.org/wiki/Double-precision_floating-point_format) on floating-point format.

You may also want to look at this
[nice article on the IEEE 64-bit floating-point standard](https://www.johndcook.com/blog/2009/04/06/anatomy-of-a-floating-point-number/)
by John Cook.
Also, [here](https://www.nextplatform.com/2018/05/10/tearing-apart-googles-tpu-3-0-ai-coprocessor/) is an interesting article on Google's TPU processor, which uses a different floating-point format.


# References for today's lecture

Sections 2.8 (effect of roundoff errors)
and 2.9 (norms and condition numbers) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# Outline

- Norm and condition number
   - Norm of a vector: (Euclidean) 2-norm, (Manhattan) 1-norm, infinity norm
   - Norm of a matrix 
   - Theorems about norms
   - Condition number of a matrix 
   - Sensitivity analysis of Ax = b [later]

- cs111 routines:
  - cs111.hilbert()

- numpy/scipy routines:
  - npla.norm()
  - npla.cond()


