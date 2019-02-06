---
num: "lect08"
lecture_date: 2019-02-04
desc: "How floating-point works"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

None; do the sample midterm before section on Tuesday.

# References for today's lecture

Section 1.7 (floating-point arithmetic) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book, 
and this [Wikipedia page](https://en.wikipedia.org/wiki/Double-precision_floating-point_format) on floating-point format.

[Here's a nice article on the IEEE 64-bit floating-point standard](https://www.johndcook.com/blog/2009/04/06/anatomy-of-a-floating-point-number/)
by John Cook.

Also, [here](https://www.nextplatform.com/2018/05/10/tearing-apart-googles-tpu-3-0-ai-coprocessor/) is an interesting article on Google's TPU processor, which uses a different floating-point format.

# Outline

Matrix condition number:
   - Sensitivity analysis of Ax = b 
   - Condition number of a matrix 

Floating-point arithmetic:
   - Machine epsilon: when 1 + x == x
   - How the bits work
   - Parameters of floating-point systems

numpy/scipy routines:
   - npla.cond()
   - np.finfo(np.float64)
