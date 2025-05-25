# EX 32 C program to display Hardware details such as price, product name and price using structure.
## DATE:
## Aim:
To write a C program to display Hardware details such as price, product name and price using structure.

## Algorithm:
1. Start.
2. Define a variables.
3. Write a program to display hardware details such as price, product name and price 
using structure.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End. 

## Program:
```
#include<stdio.h> 
struct hardware
{
   char qr[10];
   char product[10]; 
   int price;
}j[10];
int main()
 {
    int i; 
    for(i=0;i<3;i++)
    scanf("%s%s%d",j[i].qr,j[i].product,&j[i].price); 
    for(i=0;i<3;i++)
    printf("QRcode:%s\nproduct:%s\nprice :%d\n",j[i].qr,j[i].product,j[i].price);
 }
```
## Output:
![Screenshot 2025-05-07 144736](https://github.com/user-attachments/assets/5f394a32-ae50-474f-a70e-d848ab0c75a7)


## Result:
Thus the program was executed and the output was verified successfully.
