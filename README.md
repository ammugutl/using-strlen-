# using-strlen-
#include<stdio.h>
#define MAX_SIZE 100
int main()
{
    char text[MAX_SIZE];
    char * str =text;
    int count=0;
    printf("Enter the String: ");
    gets(text);
    //scanf("%s",text);
    while(*(str++)) count++;
    printf("Length of text is %d for the String %s",count,text);
    return 0;
}
