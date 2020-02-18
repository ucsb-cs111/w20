---
num: "lect12"
lecture_date: 2020-02-18
desc: "Eigenvalues, eigenvectors, graphs, and matrices"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next time, read the rest of ["The $25,000,000,000 Eigenvector"](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf).


# Outline for this week's lectures, with references

1() Eigenvalues and eigenvectors (NCM Sections 10.1, 10.2, 10.5; [Gil Strang video lecture](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/) number 21).

2() Graphs and adjacency matrices ([Lecture slides](https://github.com/ucsb-cs111/w20-lecture-files/blob/master/lecture_files/cs111-slides-04-PageRank.pdf); [Wolfram article "adjacency matrix"](http://mathworld.wolfram.com/AdjacencyMatrix.html), but note that for a directed graph each edge (v,w) only makes A[w,v] == 1, and not A[v,w]).

3(a) PageRank: The eigenvalue connection ([$25B paper](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf) Sections 1, 2.1).

3(b) PageRank: Modifying the matrix to make it work ([$25B paper](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf) Sections 2.2, 3.1).

4(a) Computing the eigenvector by the power method ([$25B paper](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf) Section 4).

4(b) The power method with a sparse matrix (Homework h06).



# Outline of today's lecture

- Eigenvalues and eigenvectors: definitions.
- Three theorems about an n-by-n real matrix A:
  - A has at least one and at most n eigenvalues, and at most n linearly independent eigenvectors.
  - The eigenvalues of A and A.T are the same, though the eigenvectors usually aren't.
  - If A is symmetric,
    - All the eigenvalues of A are real.
    - A has n linearly independent eigenvectors, which can be chosen to be orthogonal.
- Adjacency matrix of a graph
  - In our adjacency matrices, edges go _from_ columns _to_ rows. (Some people do it the other way around.)
  - indegree and outdegree of a vertex.
- The PageRank problem: which web pages are most important?
  - important = lots of pages point to you? (ranking by indegree)
  - important = lots of important pages point to you? (sounds like an eigenvector problem)


- numpy/scipy routines:
  - np.random.randn()
  - spla.eig()
  - np.sum()
  - np.sort()
  - np.argsort()
