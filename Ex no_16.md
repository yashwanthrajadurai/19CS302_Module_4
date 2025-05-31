EX NO 16 : C PROGRAM TO FIND MINIMUM BETWEEN THREE FRACTION NUMBERS USING CONDITIONAL OPERATOR.

AIM:

To write a program to find minimum between three fraction numbers using conditional operator.

ALGORITHM:

1. Start.
2. Define a variables a,b,c,min.
3. Write program to find minimum numbers.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

PROGRAM:

#include <stdio.h>

int main() {

float a, b, c, min;

scanf("%f%f%f", &a, &b, &c);

// Finding minimum using conditional operator

min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min);

return 0;

}

OUTPUT:

![Screenshot 2025-05-15 160333](https://github.com/user-attachments/assets/050bfea8-e38c-475d-862d-95097a259c2f)

RESULT:

Thus, the program is executed and verified successfully.
