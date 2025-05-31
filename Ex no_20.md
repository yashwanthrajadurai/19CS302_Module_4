# EX 20 C program to convert the given string to lowercase without using string functions.

## AIM:
To write a C program to convert the given string to lowercase without using string functions.

## Algorithm

Start.

Define the required variable.

Convert the string to lowercase.

Read the value using scanf.

Print out the answer.

End..


## Program:

#include <stdio.h>

int main() {

 char str[100];
 
 int i = 0;
 
 scanf("%s", str); 
 
 while (str[i] != '\0') {
 
 if (str[i] >= 'A' && str[i] <= 'Z') {
 
 str[i] = str[i] + 32; }
 
 i++; }
 
 printf("Lowercase string: %s\n", str);
 
 return 0;

}

## Output:

![Screenshot 2025-05-26 101756](https://github.com/user-attachments/assets/3789516a-967a-4290-ae02-1feb78e514e3)


## Result:
Thus the program was executed and the output was verified successfully.
