### Program20: Write a code to dispaly fibonacci series.
```c
#include<stdio.h>
int fibonacci(int n)
{
if(n<=1)
return n;
else
return(fibonacci(n-1)+fibonacci(n-2));
}
int main()
{
int n;
printf("enter number of elements to print - >");
scanf("%d",&n);
for (int i=0;i<n;i++)
{
printf("%d",fibonacci(i));
}
printf("\n");
return 0;
}
```
**Output:enter number of elements to print - >**
