### Program12: Write a code to display continue program.
```c
#include<stdio.h>
int main()
{
int i=0;
while (i<10)
{
if(i==5)
{
i++;
continue;
}
printf("%d\n",i);
i++;
}
return 0;
}
```
**Output: 0
1
2
3
4
6
7
8
9**
