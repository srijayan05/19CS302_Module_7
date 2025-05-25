# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE:
## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE: 
## Aim:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm:
1. Start.
2. Define a variables.
3. Write a program to read a file name from user and create that file and insert student
roll numbers in to that file.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## Program:
```
#include <stdio.h>
int main()
{
    FILE *f;
    f=fopen("Hospital.txt","w");
    if(f==NULL)
    printf("Unable to create or open the file.\n");
    else
    printf("File Created Successfully\n");
    printf("File Opened\n");
    fclose(f);
    printf("File Closed");
}
```
## Output:
![Screenshot 2025-05-07 151044](https://github.com/user-attachments/assets/1e6fc828-c7e2-4499-a0cc-db9c9812b501)



## Result:
Thus the program was executed and the output was verified successfully.

```
/*
C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
Developed by: 
RegisterNumber:  
*/
```

## Output:



## Result:
Thus the program was executed and the output was verified successfully.
