# EX-3(D)     POSITIVE ARRAY ELEMENTS

## AIM:
To write a C Program to count total number of positive elements in an array.

## ALGORITHM:
1. Start the program.
2. Read a variable.
3. Read the array values n number of times.
4. If the array value can be divided by 2 then increment count by 1.
5. Display result.
6. Stop the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
   int n,i,a[10],c=0;
   scanf("%d",&n);
   for(i=1;i<=n;i++)
   {
      scanf("%d",&a[i]);
      if(a[i]>0)
      c++;
  }
  printf("count of positive numbers in array: %d",c);
}
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-03-4d/assets/121418522/49de2ea2-f244-4ffeb23d-e3f84ca2cb3d)

## RESULT:
Thus the program to count total number of positive elements in an array has been
executed successfully.
