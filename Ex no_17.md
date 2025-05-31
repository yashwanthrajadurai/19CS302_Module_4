EX NO 17 : C PROGRAM TO COMPARE TWO STRINGS WITHOUT STRCMP FUNCTION

AIM:

To write a program to compare two strings without strcmp() function.

ALGORITHM:

1. Start.
2. Define a variables.
3. Write program to compare two strings using nested for loop and if statement.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.


PROGRAM:

#include <stdio.h>

int main() {

 char str1[100], str2[100];
 
 int i = 0, flag = 0;
 
 scanf("%s", str1);
 
 scanf("%s", str2);
 
 while (str1[i] != '\0' || str2[i] != '\0') {
 
 if (str1[i] != str2[i]) {
 
 flag = 1;
 
 break;
 
 }
 
 i++; }
 
if (flag == 0)

printf("Strings are equal.\n");

else

 printf("Strings are not equal.\n");
 
 return 0;

}

OUTPUT:

![image](https://github.com/user-attachments/assets/2fa5affc-df5b-4ee3-84c5-aa54f385017e)

RESULT:

Thus, the program is executed and verified successfully.
