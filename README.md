Download Link: https://assignmentchef.com/product/solved-csci-2500-assignment-1-matrix-multiplication
<br>
For this assignment we will be performing <a href="https://en.wikipedia.org/wiki/Matrix_multiplication_algorithm">matrix multiplication</a>. We will be revisiting this topic in the future but for now we are implementing the algorithm in C.

Following the template below, ask for the dimensions of both matrices. Once it has been confirmed that the matrices can be multiplied, ask afor the values contained within each matrix. Your program should then output the first and second matrix as well as the resulting matrix product.

Your task is to fill in the functions to complete the program skeleton given in the template file. This is a relatively short program to ensure everyone is up to speed on C programming topics. Your program should accept non-negative integer values for each element in the matrix. It should exit immediately upon invalid matrix dimensions.

Below are some sample output. Note that your program should match these samples exactly.

bash-3.2$ ./a.out

How many rows are in the first matrix?

2

How many columns are in the first matrix?

3

How many rows are in the second matrix?

3

How many columns are in the second matrix? 1

Please enter the values for the 2 x 3 matrix:

1 2 3

4 5 6

Please enter the values for the 3 x 1 matrix:

7

8

9

1 2 3

4 5 6

multiplied by

7

8

9

1

is:

50

122 bash-3.2$ ./a.out

How many rows are in the first matrix?

4

How many columns are in the first matrix?

5

How many rows are in the second matrix?

6

How many columns are in the second matrix? 7

Invalid matrix multiplication!

bash-3.2$ ./a.out

How many rows are in the first matrix?

2

How many columns are in the first matrix?

2

How many rows are in the second matrix?

2

How many columns are in the second matrix? 2

Please enter the values for the 2 x 2 matrix:

1 2

3 4

Please enter the values for the 2 x 2 matrix:

5 6

7 8

1 2

3 4

multiplied by

5 6

7 8

is:

19 22 43 50 bash-3.2$ exit

2