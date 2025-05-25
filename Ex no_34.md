# EX 34 C program to read a file name from user and create that file and insert student roll numbers in to that file.
## DATE:
## Aim:
To write a C program to read a file name from user and create that file and insert student roll numbers in to that file.

## Algorithm:
1. . Start.
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
#include <stdlib.h>
int main()
 {
    char filename[100];
    int n, roll;
    FILE *fp;
    scanf("%s", filename);
    fp = fopen(filename, "w");
    if (fp == NULL)
    {
        printf("Unable to create or open the file.\n");
        return 1;
    }
    printf("%s Opened\n", filename);
    scanf("%d", &n);
    for (int i = 0; i < n; i++)
    {
        scanf("%d", &roll);
        fprintf(fp, "%d\n", roll);
    }
    fclose(fp);
    printf("Data added Successfully\n");
    return 0;
 }

```

## Output:
![Screenshot 2025-05-07 150225](https://github.com/user-attachments/assets/8c6b9bd3-562c-4463-8f4a-7c270c70a552)

## Result:
Thus the program was executed and the output was verified successfully.
