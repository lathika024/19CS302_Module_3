# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
1. Start.
2. Declare a integer variable
3. Define a function named dectobin.
4. Return the integer.
5. Read the value using scanf.
6. Convert decimal to binary value.
7. Print the dectobin
8. End.   

## Program:
```
Program to convert a given decimal value to binary using function without arguments with return type
Developed by DEEPASREE
Register number:212222060036
#include<stdio.h>
Int dectobin(int d){
int bin =0,base=1,rem; 
while(d>0)
{
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10;
}
printf(" = %d in binary",bin); 
return 0;
}
int main()
{
int dec; 
scanf("%d",&dec);
printf("%d in decimal",dec); 
dectobin(dec);
return 0;
```

## Output:

<img width="769" height="282" alt="444157326-9d0cc919-7417-45ab-bb86-a3d9a9cc2ff7" src="https://github.com/user-attachments/assets/eb8dd7d1-2996-4509-bbb2-e242be658ee3" />


## Result:
Thus the program was executed and the output was verified successfully.
