# EX 29 C program to create two float variables using calloc() and find minimum among them.
## DATE:
## AIM:
To write a C program to create two float variables using calloc() and find minimum among them.

## Algorithm
1.Start.

2.Initialize two variables value of calloc().

3.Prompt the user to enter values.

4.Read the values using scanf.

5.Find minimum and print result

6.End.

## Program:
```
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *num1, *num2, minimum;
 num1 = (int *)calloc(1, sizeof(int));
 num2 = (int *)calloc(1, sizeof(int));
 num1= 5.8 , num2 = 6.5;
 minimum = (*num1 < *num2) ? *num1 : *num2;
 printf("%d\n", minimum);
 free(num1);
 free(num2);
```

## Output:

<img width="438" height="175" alt="image" src="https://github.com/user-attachments/assets/bc2fa494-b68a-4eee-8bfc-5dfcbcf2f6f5" />


## Result:
Thus the program was executed and the output was verified successfully.
