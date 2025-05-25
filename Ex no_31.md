# EX 31 C program to find the smallest among three numbers using Structure.
## DATE:
## Aim:
To write a C program to find the smallest among three numbers using Structure.

## Algorithm:
1. Start.
2. Define a variables a,b,c.
3. Write program to find the smallest among the three numbers.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End  

## Program:
```
#include <stdio.h>
struct Numbers
{
    int a,b,c;
};
int main()
{
    struct Numbers num;
    printf("Enter three integers:\n");
    scanf("%d %d %d", &num.a, &num.b, &num.c);
    int smallest = num.a;
    if (num.b < smallest)
        smallest = num.b;
    if (num.c < smallest)
        smallest = num.c;
    printf("The smallest number is: %d\n", smallest);
    return 0;
}
```
## Output:
![Screenshot 2025-05-07 144258](https://github.com/user-attachments/assets/92f4919a-1eba-4390-b006-bf5b0627b3e6)

## Result:
Thus the program was executed and the output was verified successfully.
