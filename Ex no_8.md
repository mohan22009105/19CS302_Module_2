# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
Start.

Declare the variables.

Prompt the user to enter a value.

Read the value using scanf.

Enter number for multiplication and division.

End.  

## Program:
```
#include<stdio.h>
void multiply();
void divide();

int main()
{
    multiply(); 
    divide();   
    
    return 0;
}

void multiply()
{
    float a, b, mul;
    scanf("%f %f", &a, &b);
    
    mul = a * b;
    printf("Multiplication is: %.2f\n", mul);
}

void divide()
{
    float a, b, div;
    scanf("%f %f", &a, &b);
    
    if(b == 0){
        printf("Division not possible (Denominator is 0)\n");
    } else {
        div = a / b;
        printf("Division is: %.2f", div);
    }
}

```

## Output:

<img width="595" height="301" alt="image" src="https://github.com/user-attachments/assets/acfadf5f-86e4-4bff-aa79-8a5c392164ce" />


## Result:
Thus the program was executed and the output was verified successfully.
