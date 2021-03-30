# Lab-5
Class syntax


## Problem 1
Write a class having two private variables and one member function which will return the area of the rectangle.  Write a main function that prompts the user with the length and width of the rectangle and outputs the area.

```
class CRectangle {
    // your code here
};

PROMPT:
    Enter length of rectangle: 10
    Enter width of rectangle: 10
    Area: 100
```


## Problem 2
Write a program and input two integers in main and pass them to default constructor of the class. Show the result of the additon of two numbers.

```
class Data{
    //class definition here
    public:
       Data(int, int);
       int sum(); 
};

PROMPT:
    Enter first number: 5
    Enter second number: 5
    sum: 10
```

## Problem 3
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

## Problem 4 
Perform addition operation on complex numbers using classes and objects. The program should ask for real and imaginary part of at least 2 complex numbers, and display the real and imaginary parts of their sum.  Use -1 to stop inputting new numbers.  To parse the input, feel free to use any c/c++ string library functions to parse the input string (such as atof() or strtok()).
Note:  The array can grow in size if the user continues entering numbers.  Use malloc(), realloc() and free() to allocate more memory as needed.
```
Next number? 5 + 5j
Next number? 10 + 10j
Next number? -1

sum: 15 + 15j
```
