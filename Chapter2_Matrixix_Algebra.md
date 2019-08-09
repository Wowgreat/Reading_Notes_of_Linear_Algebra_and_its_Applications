### INTRODUCTORY EXAMPLE

#### Computer Models in Aircraft Design

- *Partitioned matrices*: A typical CFD (Computational fluid dynamics) system of equations has "sparse" coefficient matrix with mostly zero entries. Grouping the variables correctly leads to a partitioned matrix with many zero blocks. Section 2.4 introduces such matrices and describes some of their applications.
- *Matrix factorizations*: Even when written with partitioned matrices, the system of equations is complicated. To further simplify the computations, the CFD software at Boeing uses what is called an **LU** factorization of coefficient matrix. Section 2.5 discusses **LU** and other useful matrix factori

### 2.1 MATRIX OPERATIONS

#### Matrix Multiplication

- ![](img/22.png)
- Each column of **AB** is a linear combination of the columns of **A** using weights from the corresponding column of **B**
- ![](img/23.png)
- ![](img/24.png)
- ![](img/25.png)
- 