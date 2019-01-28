---
num: "lect05"
lecture_date: 2019-01-23
desc: "Solving Ax = b by Jacobi and conjugate gradients"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next Wednesday, read sections 5.1, 5.2, and 5.5 of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book.

# References for today's lecture

The sections on the
[Jacobi method](http://www.netlib.org/linalg/html_templates/node12.html)
and the
[conjugate gradient method (CG)](http://www.netlib.org/linalg/html_templates/node20.html)
from the
[Templates book](http://www.netlib.org/linalg/html_templates/report.html).

If you're interested in learning more about how CG works,
there's a great paper called
[An introduction to the conjugate gradient method without the agonizing pain](https://people.eecs.berkeley.edu/~jrs/jrspapers.html#cg) by Jonathan Shewchuk at Berkeley.
Reading it is optional for CS 111, but it's fun if you like the math.

# Outline

Interesting matrices:

   - Manipulating sparse matrices in scipy

Iterative methods for Ax = b:

   - Jacobi iteration 
   - Conjugate gradients
   - Lecture codes:
     - Jsolve()
     - CGsolve()
   - numpy/scipy routines:
     - spla.cg()

