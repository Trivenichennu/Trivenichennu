#include<stdio.h>
#include<string.h>
void main()
{
    char a[200];
    printf("enter a sentence");
    gets(a);
    int len = strlen(a);
     int count=0;
    for(int i=0;i<len;i++)
    {
        if(a[i]==' ')
            count=count+1;
    }
    printf("the no.of words is %d",count+1);

}
OUTPUT:
enter a sentencehai hello
the no.of words is 2
