---
num: "lect13"
lecture_date: 2020-02-20
desc: "Eigenvalues, eigenvectors, graphs, and matrices"
ready: true
---

* {% include lecture_files.html %}

# Reading assignment

For next Tuesday, read NCM Sections 7.1 through 7.4 (ODEs).


# Outline for this week's lectures, with references

1) Eigenvalues and eigenvectors (NCM Sections 10.1, 10.2, 10.5; [Gil Strang video lecture](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/) number 21).

2) Graphs and adjacency matrices ([Lecture slides](https://github.com/ucsb-cs111/w20-lecture-files/blob/master/lecture_files/cs111-slides-04-PageRank.pdf); [Wolfram article "adjacency matrix"](http://mathworld.wolfram.com/AdjacencyMatrix.html), but note that for a directed graph each edge (v,w) only makes A[w,v] == 1, and not A[v,w]).

3a) PageRank: The eigenvalue connection ([$25B paper](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf) Sections 1, 2.1).

3b) PageRank: Modifying the matrix to make it work ([$25B paper](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf) Sections 2.2, 3.1).

4a) Computing the eigenvector by the power method ([$25B paper](https://github.com/ucsb-cs111/w19-lecture-files/blob/master/02.11/25_Billion_Eigenvector_Original.pdf) Section 4).

4b) The power method with a sparse matrix (Homework h06).



# Outline of today's lecture

- Intuition for PageRank as an eigenvalue problem
- Modifying the matrix to make the intuition work
  - Column scaling (and column stochastic matrices)
  - Dealing with dangling vertices
  - Making the graph strongly connected: The 15% solution
- Computing the eigenvector: the power method
- Example: harvard.edu web crawl
- Example: a million-page web crawl

- numpy/scipy routines:
  - spla.eig()
  - np.sum()
  - np.sort()
  - np.argsort()
  - np.argmax()

- cs111 routines:
  - cs111.pagerank1()
