# COMPLETE C LANGUAGE 

This repository contains my learning journey in C, covering basics, control structures, functions, arrays, pointers, file handling, and data structures. Ideal for beginners and students. Explore, run, and modify programs to enhance understanding. Stay tuned for updates! 🚀




Hello World is a simple program that is often used to introduce a new programming language to beginners.

## 1) Hello World Program in C

```c
#include <stdio.h>

int main() {
  printf("Hello, World!");

  return 0;
}
```

**Output**

```
Hello, World!
```

# 2)  Variable IN C


## Print Line of Text

```c
#include <stdio.h>

int main() {

  int age = 25;
  printf("C Programming");

  return 0;
}
```

**Output**

```
C Programming
```

---
## Print Variable

```c
#include <stdio.h>

int main() {

  int age = 25;
  printf("%d", age);

  return 0;
}
```

**Output**

```
25
```

---
## Print Text and Variable Together

```c
#include <stdio.h>

int main() {
  
  int age = 25;
  printf("Age: %d", age);

  return 0;
}
```

**Output**

```
Age: 25
```

---
## Change Value of Variable

```c
#include <stdio.h>

int main() {

  int age = 25;
  printf("Age: %d ", age);

  age = 31;
  printf("New age:  %d", age);

  return 0;
}
```

**Output**

```
Age: 25 New age: 31
```

---
## Change Value of Variable Example 2

```c
#include <stdio.h>

int main() {

  int age = 25;
  printf("Age: %d", age);

  age = 31;
  printf("\nNew age value: %d", age);

  return 0;
}
```

**Output**

```
Age: 25
New age value: 31
```

---
## Assign one variable to another variale

```c
#include <stdio.h>

int main() {

  int firstNumber = 33;
  printf("first Number = %d ", firstNumber);

  int secondNumber = firstNumber;
  printf("\nsecond Number = %d", secondNumber);

  return 0;
}
```

**Output**

```
first Number = 33
second Number = 33
```

## Declare Multiple Variables at once

```c
#include <stdio.h>

int main() {
    int variable1, variable2; 
    return 0;
}
```

```c
#include <stdio.h>

int main() {
    int variable1, variable2 = 25; 
    return 0;
}
```

---
## MCQ 1 

**Q. Can you guess the output of this program?**

```c
#include <stdio.h>

int main() {

  int number1 = 33;
  printf("%d ", number1);
  printf("%d", number2);

  return 0;
}
```

**Options**
a. 33
b. 3333
c. 33 33
d. '33.0'


**Correct Answer: c** 

## 3)   Data Type: int

```c
#include <stdio.h>

int main() {

  int age = 10;
  printf("%d", age);
  
  return 0;
}
```

**Output**

```
10
```

---
## Print variables and values together

```c
#include <stdio.h>

int main() {

  int age = 10;
  printf("Age = %d", number);
  
  return 0;
}
```

**Output**

```
Age = 10
```

---
## Data Type: double and float

```c
#include <stdio.h>

int main() {

  double number = 12.45;
  printf("%lf", number);
  
  return 0;
}
```

**Output**

```
12.450000
```
## Print formatted double output

```c
#include <stdio.h>

int main() {

  double number = 12.45;
  printf("%.2lf", number);
  
  return 0;
}
```

**Output**

```
12.45
```
---
## Print float and double

```c
#include <stdio.h>

int main() {

  double number = 12.45;
  float number1 = 10.9f;

  printf("%.2lf", number);
  printf("\n%f", number1);  

  return 0;
}
```

**Output**

```
12.45
10.900000
```

---
## Print formatted double and float type

```c
#include <stdio.h>

int main() {

  double number = 12.45;
  float number1 = 10.9f;

  printf("%.2lf", number);
  printf("\n%.1f", number1);  

  return 0;
}
```

**Output**

```
12.45
10.9
```

---
## double with exponential number

```c
#include <stdio.h>

int main() {
  
  double number = 5.5e6;
  printf("%lf", number);
  
  return 0;
}
```

**Output**

```
5500000.000000
```

---
## Data Type: char

```c
#include <stdio.h>

int main() {

  char character = 'z';
  printf("%c", character);

  return 0;
}
```

**Output**

```
z
```

---
## Print numeric value of characters

```c
#include <stdio.h>

int main() {

  char character = 'z';
  printf("%c", character);
  printf("  %d", character);

  return 0;
}
```

**Output**

```
z  122
```

---
## sizeof() Data Types

```c
#include <stdio.h>

int main() {

  int age;
  double number;

  printf("int size = %zu", sizeof (age));
  printf("\ndouble size = %zu", sizeof(number));

  return 0;
}
```

**Output**

```
int size = 4
double size = 8
```

---
## MCQ 

Q. What is the output of the following code?

```c
#include <stdio.h>

int main() {
  int a = 5;
  float a = 9.3;
  
  printf("%d", a);
}
```
**Options**
- a. 5
- b. 9.3
- c. 14.3
- d. Error

**Answer d**


## 4)  Take Input
```c
#include <stdio.h>

int main() {
  
  int age;
  
  scanf("%d", &age);

  printf("Age = %d", age);
  
  return 0;
}
```

**Output**

```
22
Age = 22
```


#### Show message to ask for input

```c
#include <stdio.h>

int main() {
  
  int age;
  
  printf("Enter input value: ");
  scanf("%d", &age);

  printf("Age = %d", age);
  
  return 0;
}
```

**Output**

```
Enter input value: 22
Age = 22
```

---
## Take double input

```c
#include <stdio.h>

int main() {
  
  double number;
  char alphabet;
  
  printf("Enter double value: ");
  scanf("%lf", &number);

  printf("Enter character value: ");
  scanf("\n%c", &alphabet);

  printf("Number: %lf", number);
  printf("\nCharacter: %c", alphabet);
  
  return 0;
}
```

**Output**

```
Enter double value: 22.1
Enter character value: z
Number: 22.100000
Character: z
```

---
## Take multiple Input

```c
#include <stdio.h>

int main() {
  
  double number;
  char alphabet;
  
  printf("Enter input values: ");
  scanf("%lf %c", &number, &alphabet);
  
  printf("Number: %lf", number);
  printf("\nCharacter: %c", alphabet);
  
  return 0;
}
```

**Output**

```
Enter input values: 30.6
c
Number: 30.600000
Character: c
```

---
## MCQ 
Q. What is the correct way to take double input?

**Options**
1. scanf("%d", &input);
2. scanf("%f", &input);
3. scanf("%lf", &input);
4. scanf("%c", &input);

**Answer: 3**


## 5)  Comments in C
```c
#include <stdio.h>

int main() {

  // create a variable
  int data = 34;

  // print the value of data variable
  printf("Data = %d", data);

  return 0;
}

```

**Output**

```
Data = 34
```


#### Comment and code can be on the same line like this


```c
#include <stdio.h>

int main() {

  int data = 34;    // create a variable

  printf("Data = %d", data);   // print the variable

  return 0;
}

```

**Output**

```
Data = 34

```

---
## Prevent Executing Code Using Comments

```c
#include <stdio.h>

int main() {
    
  int age;
  double height;
  
  printf("Enter the age: ");
  scanf("%d", &age);
  
  printf("Enter the height: ");
  scanf("%lf", &height);
  
  printf("Age = %d", age);
  printf("\nHeight = %.1lf", height);

  return 0;
}

```

**Suppose, height input is not required so we will comment it out**

```c
#include <stdio.h>

int main() {
    
  int age;
  // double height;
  
  printf("Enter the age: ");
  scanf("%d", &age);
  
  // printf("Enter the height: ");
  // scanf("%lf", &height);
  
  printf("Age = %d", age);
  // printf("\nHeight = %.1lf", height);

  return 0;
}

```
**Output**

```
Enter the age: 29
Age = 29

```
---
## Multiline Comments in C Programming

```c
This program takes age input from the user
It stores it in the age variable
And, print the value using printf()

#include <stdio.h>

int main() {
    
  int age;
  
  printf("Enter the age: ");
  scanf("%d", &age);
 
  printf("Age = %d", age);

  return 0;
}

```

**Multiline commenting above program**


```
/* This program takes age input from the user
It stores it in the age variable
And, print the value using printf() */

#include <stdio.h>

int main() {
    
  int age;
  
  printf("Enter the age: ");
  scanf("%d", &age);
 
  printf("Age = %d", age);

  return 0;
}

```
**Output**

```
Enter the age: 29
Age = 29

```
## Keyboard Shortcut
### Cmd + shift + / for multiline comments

```
/* This program takes age input from the user
It stores it in the age variable
And, print the value using printf() */

#include <stdio.h>

int main() {
    
  int age;
  
  printf("Enter the age: ");
  scanf("%d", &age);
 
  printf("Age = %d", age);

  return 0;
}

```
###  Cmd + / for singleline comment

```c
// This program takes age input from the user
// It stores it in the age variable
// And, print the value using printf()

#include <stdio.h>

int main() {
    
  int age;
  
  printf("Enter the age: ");
  scanf("%d", &age);
 
  printf("Age = %d", age);

  return 0;
}

```

---
## MCQ
Q.  What is the correct way to comment in C programming?

**Options**
1. //
2. \#
3. \<!--->
4. All of the above

**Answer: 1**



