### Program21: Write a code to display factorial of number.
```c
#include<stdio.h>
long int fact(int n)
{
if(n<=1)
return 1;
else
return fact(n-1)*n;
}
int main()
{
int n;
printf("enter a number:");
scanf("%d",&n);
printf("factorial of %d=%ld\n",n,fact(n));
return 0;
}
```
**Output:enter a number:8
factorial of 8=40320**
