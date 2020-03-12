---
num: "lect18"
lecture_date: 2020-03-12
desc: "Applications of SVD"
ready: true
---


# References for this week's lectures

NCM Sections 10.1, 10.2, 10.10, 10.11
A very retro [video](https://www.youtube.com/watch?v=R9UoFyqJca8),
made in 1976 by the author of NCM,
that visualizes the computation of the SVD.

# Outline

- Singular value decomposition:
  - rank(A) = # of nonzero singular values
  - 2-norm(A) = max singular value
  - Frobenius norm of A = sqrt(sum(singular values))
  - Determinant of A = product(singular values)
  - A = sum_i (s_i * outerproduct(u_i, v_i))

- Low-rank approximation
  - Theory
  - Principal components
  - Image compression

- Computing the SVD: watch the [video](https://www.youtube.com/watch?v=R9UoFyqJca8)

- numpy/scipy routines:
  - spla.svd()
