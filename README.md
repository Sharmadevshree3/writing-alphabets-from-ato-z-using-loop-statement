# writing-alphabets-from-ato-z-using-loop-statement
#include <stdio.h>

int main()
{
    char ch;
    printf("alphabets from a-z: \n ");
    for(ch ='a'; ch <='z'; ch++)
    {
        printf("%c\n", ch);
    }

    return 0;
}
