# Lab-8
Class syntax



## Problem 1
Write a c++ class called 'student' with

Data members: name(char type or string), grades (double array)

The program asks the user to enter name and all grades one at a time until they enter -1. Then mean() calculates the mean note and disp() displays name and total mean of all grades  screen in different lines.
Note:  The array can grow in size if the user continues entering numbers.  Use malloc(), realloc() and free() to allocate more memory as needed.  Also, you may use the string type from the string header file (#include <sttring>).

```
Student name: Jorge Ortiz
Enter grade: 100
Enter grade: 99
Enter grade: -1

Jorge Ortiz
average: 99.5
```

## Problem 2 
Perform addition operation on complex numbers using classes and objects. The program should ask for real and imaginary part of at least 2 complex numbers, and display the real and imaginary parts of their sum.  Use -1 to stop inputting new numbers.  To parse the input, feel free to use any c/c++ string library functions to parse the input string (such as atof() or strtok()).
Note:  The array can grow in size if the user continues entering numbers.  Use malloc(), realloc() and free() to allocate more memory as needed.
```
Next number? 5 + 5j
Next number? 10 + 10j
Next number? -1

sum: 15 + 15j
```

Operator overloading syntax


## Problem 3
Write a Matrix class, that holds an matrix of doubles, and overwrite the copy constructor, addition(+), subtraction(-),  multiplication(\*).

```
Matrix M(3,3);
Matrix N(3,2);

K=M*N;
A=M+M;
B=M-M;
```

