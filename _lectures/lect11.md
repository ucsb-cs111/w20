---
num: "lect11"
lecture_date: 2020-02-13
desc: "How floating-point works"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next week, read NCM Sections 10.1, 10.2, and 10.5,
and ["The $25,000,000,000 Eigenvector"](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf).


# References for today's lecture

Section 1.7 (floating-point arithmetic) of the
[NCM](http://www.cs.ucsb.edu/~gilbert/cs111/chapters/) book, 
and this [Wikipedia page](https://en.wikipedia.org/wiki/Double-precision_floating-point_format) on floating-point format.

You may also want to look at this
[nice article on the IEEE 64-bit floating-point standard](https://www.johndcook.com/blog/2009/04/06/anatomy-of-a-floating-point-number/)
by John Cook.
Also, [here](https://www.nextplatform.com/2018/05/10/tearing-apart-googles-tpu-3-0-ai-coprocessor/) is an interesting article on Google's TPU processor, which uses a different floating-point format.


# Outline

- A few more words about matrix condition number

- Floating-point arithmetic 

- Backward error analysis and error bounds on partial pivoting [didn't get to this]

- cs111 routines:
  - cs111.print_float64()

- numpy/scipy routines:
  - np.inf()
  - np.nan()
  - np.isinf()
  - np.isnan()
