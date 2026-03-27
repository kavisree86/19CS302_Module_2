# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:
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
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: 
RegisterNumber:  
*/
```
```
#include<stdio.h> 
void multiply(int a,int b); 
void div(int a,int b); 
int main () 
{ 
int a,b; 
scanf("%d%d",&a,&b); 
multiply(a,b); 
div(a,b); 
} 
void multiply(int a,int b) 
{ 
int product; 
product= a*b; 
printf("Multiplication: %d",product); 
} 
void div(int a,int b) 
{ 
int result; 
result=a/b; 
printf("\nDivision: %d",result); 
}
```

## Output:

<img width="597" height="195" alt="image" src="https://github.com/user-attachments/assets/d942673b-1ce2-488e-8e98-57570e564a58" />


## Result:
Thus the program was executed and the output was verified successfully.
