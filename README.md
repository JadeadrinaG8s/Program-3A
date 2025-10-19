# Program-3A
C module 3
EX NO-3)a)a Program to convert a given decimal value to binary using function with arguments without return type.
DATE:19/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO write a Program to convert a given decimal value to binary using function with arguments without return type.
ALGORITHM:
1)take a number a input from the user.2)divide the number by 2 and store the remainder using while loop 3)reverse the string and print it using for loop 
PROGRAM:
```
#include <stdio.h>
void binary(int k)
{
    int arr[32];
    int i=0;
    while(k>0)
    {
        arr[i]=k%2;
        k=k/2;
        i++;
    }
    for(int j=i-1;j>=0;j--)
    {
        printf("%d",arr[j]);
    }
    printf(" in binary");
    printf("\n");
}
int main()
{
    void binary(int);
    int a;
    scanf("%d",&a);
    printf("%d in decimal = ",a);
    binary(a);
}
```
OUTPUT:
<img width="911" height="258" alt="Screenshot 2025-10-19 220106" src="https://github.com/user-attachments/assets/8f0ecf4a-c9f6-4291-b62b-601b172aaf21" />
RESULT:
Thus,a Program to convert a given decimal value to binary using function with arguments without return type has been successfully executed.

