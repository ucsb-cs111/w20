---
num: "lect17"
lecture_date: 2020-03-10
desc: "Singular value decomposition"
ready: true
---

* {% include lecture_files.html %}

# References for this week's lectures

NCM Sections 10.1, 10.2, 10.10, 10.11

# Outline

- Matrix factorizations, old and new:
  - Gaussian elimination with partial pivoting: P @ A = L @ U
  - Cholesky factorization of SPD matrix: A = R.T @ R
  - Orthogonal factorization: A = Q @ R
  - Eigenvalues: A @ X = X @ S
  - Eigenvalues of SPD matrix: A = V @ S @ V.T
  - Singular value decomposition: A = U @ S @ V.T

- Singular value decomposition:
  - Geometry: m-by-n matrix A maps the unit sphere in Rn to an ellipsoid in Rm
  - Two orthogonal bases, one in domain space Rn and one in range space Rm
  - rank(A) = # of nonzero singular values
  - range(A) and nullspace(A) from U and V
  - 2-norm(A) = max singular value
  - Frobenius norm of A = sqrt(sum(singular values))
  - Determinant of A = product(singular values)
  - A = sum_i (s_i * outerproduct(u_i, v_i))

- Computing the SVD

- Low-rank approximation
  - Theory
  - Principal components
  - Image compression

- numpy/scipy routines:
  - spla.svd()
