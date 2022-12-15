### Program26: Write  a code to display pallidromic .
```c
include<stdio.h>
int main()
{
int x,y,rev=0,rem;
printf("Enter the number:");
scanf("%d",&x);
y=x;
while(x>0)
{
        rem=x%10;
        rev=rev*10+rem;
        x=x/10;
}
if(y==rev)
{
        printf("The number is Palindromic");
}
else
{
        printf("The number is not Palindromic");
}
return 0;
}
```
**Output:enter a number:**
