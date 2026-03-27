# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
Start.
Declare the variables.
Prompt the user to enter a value.
Read the value using scanf.
Enter factorial of the number.
End.   

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: 
RegisterNumber:  
*/
```

```
#include <stdio.h> 
int main() { 
    int n, i; 
    unsigned long long factorial = 1; 
    scanf("%d", &n); 
 
    if (n < 0) { 
        printf("Factorial is not defined for negative numbers.\n"); 
    } else { 
        for (i = 1; i <= n; i++) { 
            factorial *= i; 
        } 
        printf("Factorial of %d = %llu\n", n, factorial); 
    } 
    return 0; 
}
```

## Output:
<img width="518" height="199" alt="image" src="https://github.com/user-attachments/assets/91be48c1-6a51-4548-8fe8-d653c3c61c2c" />



## Result:
Thus the program was executed and the output was verified successfully.
