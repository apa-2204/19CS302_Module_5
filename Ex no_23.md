# EX 23 C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
## DATE: 02/05/2025
## AIM:
To write a C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## Algorithm
1. Start. 
2. Define a variables. 
3. Write program to to store and display the name, id, age and salary of an employee 
using structure(using array of structure). 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End. 

## Program:
```
#include<stdio.h> 
struct employee 
{ 
int id,age,salary; 
char name[30]; 
}emp[100];  
 
int main() 
{ 
int i,n; 
scanf("%d",&n); 
for(i=0;i<n;i++) 
{ 
scanf("%d %s %d %d",&emp[i].id,emp[i].name,&emp[i].age,&emp[i].salary); 
} 
printf("Employee Details\n"); 
for(i=0;i<n;i++) 
 
printf("%d %s %d %d\n",emp[i].id,emp[i].name,emp[i].age,emp[i].salary);}
```

## Output:
![image](https://github.com/user-attachments/assets/4736ac41-9b94-4dab-b59f-0b0f3ed2249d)



## Result:
Thus the program was executed and the output was verified successfully.
