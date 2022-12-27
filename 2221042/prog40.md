### write a code to display strrev code.
```c
#include <stdio.h>
#include <string.h>
void strrev(char *str){
    int len = strlen(str);
    char temp;
    for(int i=0; i<len/2;i++){
        temp = str[i];
        str[i] = str[len-1-i];
        str[len-1-i] = temp;
    }
}
int main() {
    char str1[50],str2[50];
    printf("Enter a string -> ");
    scanf("%s",str1);
    strcpy(str2,str1);
    strrev(str2);
    printf("Reverse of %s = %s\n",str1,str2);
    return 0;
}
```
**Output:
Enter a string -> car
Reverse of Automobile = rac**
