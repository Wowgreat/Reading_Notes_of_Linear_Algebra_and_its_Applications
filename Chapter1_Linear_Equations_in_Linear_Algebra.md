### 1.1 and 1.2

1. A **system of linear equations** is said to be consistent if it has either one solution or infinitely many solutions; a system is inconsistent if it has no solution.

2. Two matrices are called row equivalent if there is a sequence of elementary row operations that transforms one matrix into the other.

3. If the **augmented matrices** of two linear systems are row equivalent, then the two systems have the same solution set.

4. A rectangular matrix is in **echelon form** (or row echelon form) if it has the following three properties:

   (1). All nonzero rows are above any rows of all zeros

   (2). Each leading entry of a row is in a column to the right of the leading entry of the row above it

   (3). All entries in a column below a leading entry are zeros

   We can get property 3 by property 2

   If a matrix in echelon form satisfies the fellowing additional conditions, then it is in **reduced echelon form** (or reduced row echelon form):

   (4). The leading entry in each nonzero row is 1

   (5). Each leading 1 is the only nonzero entry in its column

5. Each matrix is row equivalent to  one and only one reduced echelon matrix

6. A pivot position in a matrix A is a location in A that corresponds to a leading 1 in the reduced echelon form of A. A pivot column is a column of A that contains a pivot position.


   You could learn "the row reduction algorithm" on page 15 in <Linear algebra and its Applications 5th>

   

7. A computer program usually selects as a pivot the entry in a column having the largest absolute value. This strategy, called partial pivoting, is used because it reduces roundoff errors in the calculations.
8. The variables theses corresponding to pivot columns in the matrix are called **basic variables**, otherwise, called **free variables**
9. Whenever a system is inconsistent, the solution set is empty, even when the system has free variable. In this case, the solution set has no parametric representation

### 1.3 VECTOR Equations

- ![](img/1.png)

- ![Linear Combination](img/2.png)

  This is called a **Linear Combination** of **v1,....,vp** with wights C1，...,Cp

- ![](img/3.png)

- ![](img\4.png)

### 1.4 The MATRIX EQUATION Ax = b （Read it next time...）

- ![](img/5.png)

- ![](img/6.png)

- The equation **Ax = b** has a solution if and only if b is a linear combination of columns of **A**

- ![](img/7.png)

  **Warning** Theorem 4 is about a coefficient matrix, not an augmented matrix.

- ![](img/8.png)

  if you want proof of above theorem, you can find it page 39 in a book named <Linear_Algebra_and_Its_Applications 5th>

- To optimize a computer algorithm to compute **Ax**, the sequence of calculations should involve data stored in contiguous memory locations. The most widely used professional algorithms for matrix computations are written in Fortran, a language that stores a matrix as a set of columns. Such algorithms compute **Ax** as a linear combination of columns of **A**. In contrast, if a program is written in the popular language **C**, which stores matrices by rows, **Ax** should be computed via the alternative rule that uses the rows of **A**.

### 1.5 SOLUTION SETS OF LINEAR SYSTEMS

- A system of linear equations is said to be **homogeneous** if it can be written in the form **Ax=0**, where **A** is an m*n matrix and **0** is the zero vector in **R^m**. Such a system **Ax=0** always has at least one solution, namely, **x=0**. This zero solution is usually called the **trivial solution**.
- The **homogeneous** equation **Ax=0** has a **nontrivial solution** if and only if the equation has at least one free variable.
- ![](img/9.png)
- ![](img/10.png)

### 1.6 Applications of LINEAR SYSTEMS

- Just three Applications in this chapter.

### 1.7 LINEAR INDEPENDENCE

- ![](img/11.png)
- ![](img/12.png)
- ![](img/13.png)
- ![](img/14.png)
- ![](img/15.png)

### 1.8 INTRODUCTION TO LINEAR TRANSFORMATIONS

- ![](img/16.png)

### 1.9 THE MATRIX OF A LINEAR TRANSFORMATION

- ![](img/17.png)
- ![](img/18.png)
- ![](img/19.png)
- ![](img/20.png)
- ![](img/21.png)
