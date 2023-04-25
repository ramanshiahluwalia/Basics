
# Basic C programming
C programming language has various data types, which are used to define variables, functions, and expressions. The data types in C are classified into four categories: basic, derived, enumeration, and void. In this report, we will discuss the different data types in C and their usage in programming.

Input and Output operations are an integral part of any programming language. In C, we use different functions to print output to the screen and read input from the user. In this report, we will discuss the basic input and output functions in C with examples, explanations, and code references.




## Basic Data Types

The basic data types in C include char, int, float, and double. These data types are used to declare variables that store simple values.





````
char ch = 'a';
int i = 10;
float f = 3.14;
double d = 3.14159265359;

````


## Printing Output using printf()

The printf() function is used to print output to the screen. It is defined in the stdio.h header file. The syntax of the printf() function is:



````
printf("format string", argument1, argument2, ...);
````
## Reading Input using scanf()

The scanf() function is used to read input from the user. It is also defined in the stdio.h header file. The syntax of the scanf() function is:


## Explanations

In the first example, we use the printf() function to print a string, integer, and a float value to the screen. We use %s, %d, and %f format specifiers to print string, integer, and float values, respectively. In the second example, we only print a string to the screen using the printf() function.
In the above example, we use the scanf() function to read an integer, a float, and a character value from the user. We use %d, %f, and %c format specifiers to read integer, float, and character values, respectively. Note that we have used a space before %c to consume any whitespaces that might be present in the input buffer.

## Sample output
````
````
````
Enter an integer: 10
Enter a floating point number: 3.14
Enter a character: a

Integer: 10
Float: 3.140000
Character: a

````

## Usage
The printf() function is used to print output to the screen. It is widely used in C programs to display information to the user.

