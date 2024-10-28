# C
strings
#include <stdio.h>
#include <string.h>
int main()
{
    
    char str[50];
    printf("Enter a name with in size 10");
    fgets(str, 50, stdin);
    puts(str);
    return 0;
}
    
