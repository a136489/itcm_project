# itcm_project
Team project for the course Introduction to Computational Mathematics

### Classification of handwritten digits
It is a standard problem in pattern recognition to classify handwritte digits by
computer. If an SVD basis method is used to solve the problem, it consists of
the following two steps:
1. Training phase: For training set of known digits, compute SVD of each set of
digits of one kind, i.e., compute SVD of 10 matrices of dimensions m^2 × n_i
. Each digit is an m × m digitized image; n_i number of training digits.
2.  Classification phase: For given test digits, compute relative residual in all 10
based. If one residual is significantly smaller than all others, classify as that.
Otherwise give up, i.e., compute 10 least squares residuals.

[all topics](https://ceiba.ntu.edu.tw/course/7a770d/content/cmath2019_project.pdf)

### reference
 L. Elden. Matrix methods in data mining and pattern recognition. SIAM, 2007.