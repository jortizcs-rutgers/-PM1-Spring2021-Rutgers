# Lab-9
Operator overloading syntax

## Problem 1
Implement the transpose function and use it for doing matrix multiplication.  Write a member function for the Matrix class 'transpose()' which performs the transpose operation on the Matrix.

```
Matrix M(3,3);
Matrix N(2,3);

K=M*N.transpose();
A=M+M;
B=M-M;
```

## Problem 2
Implement a new class, 3DMatrix, which inherits from the Matrix Class.  It should represent a series of Matrix objects.  Overwrite all the operators implemented in last week's lab: addition(+), subtraction(-), and multiplication (*).
Overwrite all operators for the 3DMartix class to perform the same operations.  For multiplication, the two operands must have the same number of Matrix objects stacked,
and multiplication should be performed acrosss each corresponding Matrix index:

For example
```
M1 = 3DMatrix(3,4,2);
M2 = 3DMatrix(4,20,2);

M3 = M1*M2;  // dimensionality of M3 is (3,20,2)
```

## Problem 4 (extra credit problem)
Overload the input and output stream operators to display the Matrix and to populate a Matrix from cin;

```
INPUT: 1 2 3; 1 4 5; 1 1 9
OUTPUT:
1 2 3
1 4 5
1 1 9
```
