//# strcmp.c//
#include<stdio.h>
#include<string.h>
int main()
{
    char a[20]="jimin";
    char b[20]="jimin";
    if(strcmp(a,b)==0)
    {
        printf("compare equal.");
    }
    else
    {
        printf("not equal.");
    }
}
