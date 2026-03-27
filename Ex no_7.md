# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
Start.
Declare the variables i,j,k,n.
Prompt the user to enter a value.
Read the value using scanf.
Enter number of rows and columns.
End.  

## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: 
RegisterNumber:  
*/
```
```
#include <stdio.h> 
int main() { 
    int i, j, rows; 
    scanf("%d", &rows); 
    for (i = 1; i <= rows; i++) { 
        for (j = 1; j <= i; j++) { 
            printf("*"); 
        } 
        printf("\n"); 
    }    return 0; 
}
```

## Output:
<img width="333" height="163" alt="image" src="https://github.com/user-attachments/assets/9235f3ef-59b1-4ac2-852b-e4bb16bf18f1" />



## Result:
Thus the program was executed and the output was verified successfully.
