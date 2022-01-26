# Robotics 501: Mathematics for Robotics

ROB 501: Mathematics for Robotics, is a graduate-level course at the University of Michigan that introduces applied mathematics for robotics engineers.

Topics include vector spaces, orthogonal bases, projection theorem, least squares, matrix factorizations, Kalman filter and extensions, particle filters, underlying probabilistic concepts, norms, convergent sequences, contraction mappings, Newton Raphson algorithm, nonlinear constrained optimization, local vs global convergence, convexity, linear and quadratic programs, and randomized search strategies.

This offering of the course is from Fall 2018.

## Prerequisites
It is assumed that students know basic matrix algebra, such as how to multiply and invert matrices, what  is  the  rank  of  a  matrix,  and  how  to  compute  eigenvectors; know  how  to  compute  means  and  variances  given  a  density  of  a  continuous random variable, and conditional probability and how to compute it; know vector calculus and will review how to compute gradients of functions and what is the method of Lagrange multipliers; simple properties of complex numbers; and how to use MATLAB, including plotting, various types of multiplication, such as * vs .*  (star  vs  dot  star),  writing  a  for  loop,  or finding help.

## Lecture Videos & Notes
All lecture videos are available on YouTube:  
[ROB 501 Fall 2018 videos](https://www.youtube.com/playlist?list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH)

And [lecture notes](https://github.com/michiganrobotics/rob501/tree/main/Lecture%20Notes).

## Recitatioins
[Recitation questions and answers](https://github.com/michiganrobotics/rob501/tree/main/Recitations) are both available.

## Course Plan
| Lecture | Topic                                                      | YouTube                                                                                      | Assignments Due    |
|---------|------------------------------------------------------------|----------------------------------------------------------------------------------------------|--------------------|
| 1       | Intro & Proofs                                             | [Video](https://www.youtube.com/watch?v=2-aK25lBzvI&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=1)  |                    |
| 2       | Induction, Fundamental Theorem, & Contradiction            | [Video](https://www.youtube.com/watch?v=f559OMvSGMg&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=2)  |                    |
| 3       | Abstract Linear Algebra                                    | [Video](https://www.youtube.com/watch?v=eZxsj8k-UbY&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=3)  |                    |
| 4       | Subspaces & Linear Independence                            | [Video](https://www.youtube.com/watch?v=PL6AkVR-HUk&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=4)  | [Homework 1](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%201.pdf)         |
| 5       | Basis Vectors & Dimension                                  | [Video](https://www.youtube.com/watch?v=B-x9uuBcQac&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=5)  |                    |
| 6       | Linear Operators & Eigenvalues                             | [Video](https://www.youtube.com/watch?v=89QF687IeT8&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=6)  | [Homework 2](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%202.pdf)         |
| 7       | Similar Matrices & Norms                                   | [Video](https://www.youtube.com/watch?v=yTd33p8pmaY&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=7)  |                    |
| 8       | Inner Product Spaces                                       | [Video](https://www.youtube.com/watch?v=Gp_z3aLpTyY&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=8)  | [Homework 3](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%203.pdf)         |
| 9       | Projection Theorem & Gram-Schmidt                          | [Video](https://www.youtube.com/watch?v=Bg6JdhoHyn0&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=9)  |                    |
| 10      | Normal Equations & Least Squares                           | [Video](https://www.youtube.com/watch?v=y5Ef5UriN58&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=10) | [Homework 4](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%204.pdf)         |
| 11      | Symmetric & Orthogonal Matrices                            | [Video](https://www.youtube.com/watch?v=-rp1jsBV7x8&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=11) |                    |
| 12      | Positive Semi-Definite Matrices & Schur Complement Theorem | [Video](https://www.youtube.com/watch?v=iyvfKlZuG-g&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=12) | [Homework 5](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%205.pdf)         |
| 13      | Recursive Least Squares & Kalman Filter                    | [Video](https://www.youtube.com/watch?v=Ha2ls-aLmgs&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=13) |                    |
| 14      | Least Squares & Probability                                | [Video](https://www.youtube.com/watch?v=QwjS-0fInnQ&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=14) |                    |
| 15      | Best Linear Unbiased Estimator                             | [Video](https://www.youtube.com/watch?v=4ah5DzYjFUE&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=15) | [Homework 6](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%206.pdf)         |
| 16      | QR Factorization                                           | [Video](https://www.youtube.com/watch?v=AqPpZyLf37I&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=16) | [Exam 1](https://github.com/michiganrobotics/rob501/tree/main/Exams)             |
| 17      | Modified Gram-Schmidt & Minimum Variance Estimator         | [Video](https://www.youtube.com/watch?v=hVnJiNXJTAs&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=17) |                    |
| 18      | Probability Space & Random Variables                       | [Video](https://www.youtube.com/watch?v=dnMH9sCuudA&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=18) |                    |
| 19      | Gaussian Random Vectors                                    | [Video](https://www.youtube.com/watch?v=jPSRL_PABVI&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=19) | [Homework 7](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%207.pdf)         |
| 20      | Real Analysis & Normed Spaces                              | [Video](https://www.youtube.com/watch?v=9Hvq-Fe6YmM&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=20) |                    |
| 21      | Real Analysis & Interior of a Set                          | [Video](https://www.youtube.com/watch?v=v25gVgzrqHg&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=21) | [Homework 8](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%208.pdf)         |
| 22      | Newton-Raphson Algorithm                                   | [Video](https://www.youtube.com/watch?v=oAw2mqSoRr4&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=22) |                    |
| 23      | Cauchy Sequences                                           | [Video](https://www.youtube.com/watch?v=IVx2SvN4hQ8&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=23) | [Homework 9](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%209.pdf)         |
| 24      | Continuous Functions                                       | [Video](https://www.youtube.com/watch?v=_2CcWd4qryU&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=24) |                    |
| 25      | Weierstrass Theorem                                        | [Video](https://www.youtube.com/watch?v=DT367udR6Uc&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=25) |                    |
| 26      | Final Class & Linear Programming                           | [Video](https://www.youtube.com/watch?v=H-2_Tl-4p_A&list=PLdPQZLMHRjDIzO99aE7yAtdOHSVHMXfYH&index=26) | [Homework 10](https://github.com/michiganrobotics/rob501/blob/main/Homework/Homework%2010.pdf) & [Exam 2](https://github.com/michiganrobotics/rob501/tree/main/Exams) |

A [more detailed course plan](https://github.com/michiganrobotics/rob501/tree/main/Course%20Schedule) is available.

## Credits
- Jessy Grizzle, Director, Michigan Robotics
- Nils Smit-Anseeuw

## For more
- [University of Michigan Robotics](https://robotics.umich.edu)
- [Michigan Robotics Twitter](http://twitter.com/umrobotics)
- [Michigan Robotics Instagram](http://instagram.com/umrobotics/)
