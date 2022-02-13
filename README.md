# LUDecomposition

Ex:-AX=B , where A=LU.
    LUX=B, let Y=UX.
    LY=B.
We have to find values of X.

1) Compile and create one executable file using command(" gcc LUDecomposition.c -o output ")
2) Run the executable file "output" by using(" ./output ")
3) First input the order of matrix A.
4) Then input all the elements of matrix A one by one.
5) Input all the elements of vector B.
6) At last the output containing L, U, Y, X will be visible on screen.


1) Step 1. Read the matrix A = [aij], i,j = 1, 2, ….n and the right hand vector b = (b1, b2, …, bn)t.
2) Step 2. li1 = ai1 for i = 1, 2, …, n; u1j = a1j / l11 for j = 1, 2, …, n; uii = 1 for i = 1, 2, …, n
3) Step 3. For i, j = 2, 3, …,n compute the following
4) Step 4. //Solve the system Lz = b by forward substitution
5) Step 5. //Solve the system Ux = z by backward substitution
6) Step 6. Print x1, x2, …, xn as solution.
