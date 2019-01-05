---
title: Grading and Policies
layout: default
---


# Introduction to Computational Science

Introduction to scientific computing, emphasizing basic numerical
algorithms and the informed use of mathematical software. Matrix
computation, systems of linear equations, differential
equations. Students will learn and use the
[Matlab](https://ucsb-cs111.github.io/topics/matlab/) language.

{% include cs111_logo.html %}



| Instructor: | Prof. John R. Gilbert |
| Email: | gilbert@cs.ucsb.edu |
| Office: | Harold Frank Hall 5109 |
| Office hours: | see [my web page](https://www.cs.ucsb.edu/~gilbert) |
| Teaching assistant: | TBD |
| TA Email: | TBD  |
| TA Office hours: | TBD |
| Grader: | TBD |
| Grader Email:| TBD |


# Discussion and announcements

TODO: Edit and consider replacing with link to Piazza

There is a Google discussion group for the class at
<http://groups.google.com/group/ucsb-computer-science-111-fall-2010>. All
students are expected to join this group and to watch it for course
announcements. You may also use it to post questions for the
instructor and assistant (and answers to other people's
questions). The mailing address for posting to the group is
`ucsb-computer-science-111-fall-2010@googlegroups.com`.

# Class meetings:

|Lecture: | Monday and Wednesday 9:30-10:45, Trailer 387 (near Psych), room 101 |
|Discussion 08698: | Friday 10:00-10:50, Phelps 3519 (begins October 1) |
|Discussion 63784: | Friday 12:00-12:50, Phelps 1401 (begins October 1) |


# Textbook:

The textbook is: Numerical Computing with Matlab, by Cleve Moler. The
book has a [web site](http://www.mathworks.com/moler/index_ncm.html).

Besides the bookstore, you can:
* download the book from its web site, or
* order it from [SIAM](http://ec-securehost.com/SIAM/ot87.html), the Society for
Industrial and Applied Mathematics.

You can get a discount on the book if you are a
[member of SIAM](http://www.siam.org/membership/individual/free.php),
which is free for UCSB students (talk to Prof. Gilbert.).

# Course software and computer resources:

You'll use Matlab for all your programming in the course. It works on
the Linux computers in CSIL and on the Windows computers in the ECI
labs.

To run Matlab from your personal machine, you can:
* log in to CSIL remotely
   and [forward the graphics](https://ucsb-cs111.github.io/topics/x11_forwarding/), or
* download a copy using the UCSB Campus License
   (see: [MATLAB](https://ucsb-cs111.github.io/topics/matlab))


The course will also use the "NCM" software, which you can put on your Matlab path at CSIL in any of several ways:

| at the Matlab prompt     | `addpath /cs/class/cs111/ncm` |
| in your `startup.m` file | `addpath /cs/class/cs111/ncm` |
| when running Matlab      | `matlab -r "addpath /cs/class/cs111/ncm"` |
| `bash` command or put in `~/.bashrc` | `export MATLABPATH=/cs/class/cs111/ncm` |
| `csh` command or put in `~/.cshrc`   | `setenv MATLABPATH /cs/class/cs111/ncm` |


For the ECI lab machines or your personal machine, you can download
your own copy of NCM from the [textbook web site](https://www.mathworks.com/moler/index_ncm.html).

# Grades

|Homework assignments | 40% |
|Midterm exam | 20% |
|Final exam   | 40% |

# Midterm

Wednesday, November 3, in class.

Open book, open notes, no computers or other electronic devices.

The midterm will cover chapters 1 and 2 of the text and general
knowledge of Matlab including indexing, permutations, and so forth.

Sample exam: [2005 midterm](http://www.cs.ucsb.edu/~gilbert/cs111/old/cs111Fall2010/midterm2005.pdf). (CS 111 was called CS 110A in 2005.)

# Final exam

8:00 am - 11:00 am (sorry about that), Thursday, December 9, in classroom.

Open book, open notes, no computers or other electronic devices.

The final will cover material from the entire course.
(See the [list of topics]({{ '/info/topics' | relative_url }}))

* [Sample final exam problems](http://www.cs.ucsb.edu/~gilbert/cs111/old/cs111Fall2010/SampleFinalComplete.pdf)

# Homework policy

There will be a homework assignment every week. You may talk to each
other about the assignment, but what you submit must be your own
work. Most weeks there will be two sets of problems: one to be turned
in for a grade, and one for self-study to test your own understanding
of the course material.  All homework must be submitted in hard copy,
on paper. We strongly encourage you to write up your homework using
LaTeX, which is the standard markup language for mathematical
documents. To get you started, [here is the LaTeX](http://www.cs.ucsb.edu/~gilbert/cs111/old/cs111Fall2010/quiz/quiz.tex) for the [review quiz](http://www.cs.ucsb.edu/~gilbert/cs111/old/cs111Fall2010/quiz/quiz.pdf).


When a homework exercise requires a Matlab program, turn in four things:

1. the Matlab program listing (`.m` files; use `verbatim` mode in LaTeX)
2. the relevant lines from the diary of your Matlab session running the program
   (`\begin{verbatim}...\end{verbatim}` in
   [LaTeX](https://ucsb-cs111.github.io/topics/latex/))
3. copies of any output figures or plots (save figures as pdf's and include in LaTeX)
4. a description in English of what you did and how

Homework is due every Monday at the beginning of class, or in the
CS111 homework box in the Computer Science mailroom, 2108 HFH, by 9:00
am Monday. <span style="color:red">No late homework will be accepted
under any circumstances</span>, but I will drop your two lowest
homework grades.

If you have questions about grading of homework, talk to the grader or
the t.a. first. If you are unable to reach an agreement, make an
appointment to talk to me. <span style="color:red">The statute of
limitations for regrades is one week<span>&mdash;that is, any requests
for regrades must be made no later than one week after the homework
(or exam) was returned in class.


# Homework assignments:


* Due Wed, Sep 29: Do the review quiz. Turn this in, Wednesday in class. We will correct the quiz, but you will get full credit just for turning it in. Here are the answers to the quiz.
* Due Mon, Oct 4: Exercises 1.1, 1.5, 1.13, 1.15, 1.17. (Turn these in for a grade, in class.)
* Due Mon, Oct 11: Exercises 2.1, 2.4, 2.8, 2.10. (Turn these in for a grade.)
* Self study for Mon, Oct 11: Exercises 2.3, 2.7, 2.17. (Don't turn these in, they are to test your own understanding.)
* Due Mon, Oct 18: Exercises 2.5, 2.11, 2.16 parts a-d (Turn these in for a grade.)
* Self study for Mon, Oct 18: Exercises 2.9, 2.12, 2.14 (Don't turn these in.)
* Due Mon, Oct 25: Exercises 2.18, 2.22, 2.23, 2.25. (Turn these in for a grade.)
* Self study for Mon, Oct 25: Exercises 2.15, 2.19. (Don't turn these in.)
* Due Mon, Nov 1: Exercises 1.34, 1.35, 1.36, 1.38. (Turn these in for a grade.)
* Self study for Mon, Nov 1: Exercise 1.39. (Don't turn this in.)
* Due Mon, Nov 15: Exercises 5.2, 5.8, 7.1. (Turn these in for a grade.)
* Self study for Mon, Nov 15: Exercises 5.3, 5.11. (Don't turn these in.)
* Due Mon, Nov 22: Exercises 7.4, 7.16, 7.18. (Turn these in for a grade.)
* Self study for Mon, Nov 22: Run all the examples in Section 7.7 in Matlab. Also, do Exercise 7.2 (Don't turn these in.)
* Due Wed, Dec 1 (extension due to CSIL closure): Exercise 7.21. (This is a longer but moderately realistic problem about modeling global warming. Among other things you'll use an interpolation routine, "pchiptx", from Chapter 3. Turn this in for a grade.)
* Self study for Mon, Nov 29: Exercises 10.12, 10.14, 7.23. (Don't turn these in.)
* Class schedule, diaries, and reading assignments:

# Schedules of Classes

The schedule of future classes should be considered tentative!

* Mon Sep 27: Introduction. The fractal fern. [diary]
   * Reading: Sections 1.1 through 1.6 (intro to Matlab).

* Wed Sep 29: Systems of linear equations. [diary (you will also need to put the file temperature.mat in your home or Matlab directory)]
   * Reading: Sections 2.1 through 2.7 (Linear equations, backslash, LU).

* Mon Oct 4: Solving Ax=b, LU factorization. [diary]
   * Reading: Same as last time, sections 2.1 through 2.7.

* Wed Oct 6: LU factorization, partial pivoting, permutation vectors.
   * [diary (requires LU.mat and temperature.mat)]
   * Reading: Sections 2.10 through 2.12 (Sparse matrices, PageRank).

* Mon Oct 11: Permutations, diagonal matrices, indexing.
   * [diary, testmat.m, LU.mat]
   * Reading: Same as last time, sections 2.10 through 2.12.

* Wed Oct 13: Sparse matrices, graphs, PageRank.
   * [diary, slides, temperature.mat]
   * Reading: Sections 2.8 and 2.9 (Error and residual, norm and condition number).

* Mon Oct 18: Markov chains and PageRank. [diary, slides]
   * Reading: Section 1.7 (Floating-point arithmetic).

* Wed Oct 20: Norms and condition numbers. [diary]
   * Reading: Same as last time, section 1.7.

* Mon Oct 25: How floating-point arithmetic works. [diary]

* Wed Oct 27: Round-off error. [diary]

* Mon Nov 1: Least squares and curve fitting.

* Wed Nov 3: Midterm.

* Mon Nov 8: Iterative methods for solving linear systems. [diary, roomtemp.mat, jacobitest1.m, jacobitest2.m, jacobitest3.m]
Reading: Sections 5.1 - 5.5 (least squares) and 7.1 - 7.2 (ODEs).

* Wed Nov 10: Ordinary differential equations. Standard form, Lotka-Volterra equations. [diary, f.m, mylotka.m]
   * Reading: Sections 7.7, 7.4, 7.5, 7.6, 7.8 (ODE examples and algorithms).

* Mon Nov 15: Adam Lugowski, guest speaker: Parallel computing on graphs and matrices. [slides]
   * Reading: Sections 7.3, 7.7, 7.10.

* Wed Nov 17: ODEs: Forward Euler and BS23 algorithms. [diary, weightf.m, ode1.m, Top500, SCEC]
   * Reading: The rest of Chapter 7: sections 7.9 and 7.11 - 7.15.

* Mon Nov 22: ODEs: Stiff problems. [diary, valleyf.m]
   * Reading: Sections 10.1 - 10.3 (eigenvalues and SVD), 10.5 (eigenvalues of symmetric matrices), 10.11 (PCA).

* Wed Nov 24: All questions answered. [diary, ptf.m, eventfunction.m, event1.m]

* Mon Nov 29: Eigenvalues, eigenvectors, and SVD. [diary]

* Wed Dec 1: SVD and principal component analysis. [diary, approximation.m, spynum.m, spyimg.m, mycmap.m]

* Thu Dec 9: Final exam, 8:00 to 11:00 am.

# Other things

* Nick Trefethen on [The definition of numerical analysis](http://www.cs.ucsb.edu/~gilbert/cs111/old/cs111Fall2010/defn.pdf)
* MIT's Math 18.06, an introductory course in linear algebra,
   with Gil Strang's wonderful
   [lectures](http://web.mit.edu/18.06/www/Video/video-fall-99-new.html)
   online.
