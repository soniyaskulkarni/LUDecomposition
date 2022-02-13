# LU-Decomposition
-  LU-Decomposition or lower–upper (LU) decomposition is a matrix as the product of a lower triangular matrix and an upper triangular matrix. The product sometimes includes a permutation matrix as well. LU decomposition can be viewed as the matrix form of Gaussian elimination. 

### The LU decomposition of a matrix A is the pair of matrices L and U such that:
 - A = LU
 - L is a lower-triangular matrix with all diagonal entries equal to 1
 - U is an upper-triangular matrix
 ### The properties of the LU decomposition are:
 - The LU decomposition may not exist for a matrix A
 - If the LU decomposition exists then it is unique.
 - The LU decomposition provides an efficient means of solving linear equations.
 - The reason that L has all diagonal entries set to 1 is that this means the LU decomposition is unique. This choice is somewhat arbitrary (we could have decided that U
 must have 1 on the diagonal) but it is the standard choice.
Ex:-AX=B , where A=LU.
    LUX=B, let Y=UX.
    LY=B.
We have to find values of X.

## Steps to run program on google collab
1) Create executable file (%%writefile ludecompose.c) this will be written at the start of program :
2) For compiling follow the commands:
 - %%shell 
 - gcc ludecompose.c -o infile
 - ./infile

## Ex:-AX=B , where A=LU.
    LUX=B, let Y=UX.
    LY=B.
## If We have to find values of X.

1) Compile and create one executable file using command(" gcc LUDecomposition.c -o output ")
2) Run the executable file "output" by using(" ./output ")
3) First input the order of matrix A.
4) Then input all the elements of matrix A one by one.
5) Input all the elements of vector B.
6) At last the output containing L, U, Y, X will be visible on screen.

## Algorithm
Step 1) Read the matrix A = [aij], i,j = 1, 2, ….n and the right hand vector b = (b1, b2, …, bn)t.
Step 2) li1 = ai1 for i = 1, 2, …, n; u1j = a1j / l11 for j = 1, 2, …, n; uii = 1 for i = 1, 2, …, n
Step 3) For i, j = 2, 3, …,n compute the following
Step 4) //Solve the system Lz = b by forward substitution
Step 5) //Solve the system Ux = z by backward substitution
Step 6) Print x1, x2, …, xn as solution.
