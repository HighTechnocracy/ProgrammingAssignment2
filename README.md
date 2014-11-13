### Assignment: Caching the Inverse of a Matrix

Matrix inversion is usually a costly computation and there may be some
benefit to caching the inverse of a matrix rather than computing it
repeatedly.

I have written the following functions:

1.  `makeCacheMatrix`: This function creates a special "matrix" object
    that can cache its inverse.
2.  `cacheSolve`: This function computes the inverse of the special
    "matrix" returned by `makeCacheMatrix` above. If the inverse has
    already been calculated (and the matrix has not changed), then
    `cacheSolve` should retrieve the inverse from the cache.

Computing the inverse of a square matrix can be done with the `solve`
function in R. For example, if `X` is a square invertible matrix, then
`solve(X)` returns its inverse.

For this assignment, I have assumed the matrix supplied will always
be invertible.

In order to complete this assignment, I have done the following:

1.  Forked the GitHub repository containing the stub R files at
    [https://github.com/rdpeng/ProgrammingAssignment2](https://github.com/rdpeng/ProgrammingAssignment2)
    to create a copy under my own account.
2.  Cloned my forked GitHub repository to my computer so that I could
    edit the files locally on my machine.
3.  Edited the R file contained in the git repository and placed my
    solution in that file.
4.  Commited my completed R file into my git repository and pushed my
    git branch to the GitHub repository under my account.
5.  Submitted to Coursera the URL to my GitHub repository that contains
    the completed R code for the assignment.

### Grading

This assignment will be graded via peer assessment.
