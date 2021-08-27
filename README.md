# reverse-order
C program to display the contents of the file in reverse order

#include <stdio.h>
#include <string.h>
int main()
{
    char str[100];
    char rev[100];
    int i, j, len=0;
    
    printf(" Enter a string: ");
    gets(str);
    len = strlen(str);
    printf("The reverse string is: ");
    for(i = len - 1; i >= 0; i--) 
    {
         printf("%c", str[i]);
    }
    
    return 0;
}
