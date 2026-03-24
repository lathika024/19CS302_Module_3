# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## DATE:
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start.
2. Declare a array size value of type int.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Initialize array elements.
6. Replace all even elements to E
7. End.    

## Program:
```
program that reads a one-dimensional array of integers and replaces all even elements with 'E'

c program
#include <stdio.h>
int main() {
 int arr[100], n;
 scanf("%d", &n);
 for (int i = 0; i < n; i++) {
 scanf("%d", &arr[i]);
 }
 for (int i = 0; i < n; i++) {
 if (arr[i] % 2 == 0)
 printf("E ");
 else
 printf("%d ", arr[i]);
 }
 printf("\n");
 return 0;
}
```

## Output:

<img width="464" height="177" alt="444160991-d472aba3-d8e5-4b1c-8b87-ca0f836672e9" src="https://github.com/user-attachments/assets/4d4feb24-d018-4d2a-8526-e501bc95dcf0" />


## Result:
Thus the program was executed and the output was verified successfully.
