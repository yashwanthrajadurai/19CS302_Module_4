EX NO 18: C PROGRAM TO FIND THE FREQUENCY OF THE CHARACTER.

AIM:

To write a program to find the frequency of the character.

ALGORITHM:

1. Start.
2. Define the required variable.
3. Write program to find frequency of a character.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

PROGRAM:

#include<stdio.h>

#include<string.h>

int main()

{

int i,count=0,len;

char str[100],val[100];

scanf("%s %s",str,val);

len=strlen(str);

for(i=0;i<len;i++){

if(str[i]==val[0])

count++;

}

printf("%d",count);

}

OUTPUT:

![image](https://github.com/user-attachments/assets/710fee69-8096-4707-9985-e6833b8d4652)

RESULT:

Thus, the program is executed and verified successfully.
