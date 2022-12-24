The syntax for the for loop is:
for ( <expression_1> ; <expression_2> ; <expression_3> )
    <statement>
expression_1 is used for intializing variables which are generally used for controlling the terminating flag for the loop.
expression_2 is used to check for the terminating condition. If this evaluates to false, then the loop is terminated.
expression_3 is generally used to update the flags/variables.
The following loop initializes  to 0, tests that  is less than 10, and increments  at every iteration. It will execute 10 times.
for(int i = 0; i < 10; i++) {
    ...
}

Solution:
----------------------------------------------------------------------------------------------------------------------------------------------------
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
int main() 
{
    int a, b, i;
    scanf("%d\n%d", &a, &b);
  	// Complete the code.
    char name[][20] = {" ","one", "two", "three","four","five","six","seven", "eight","nine"};
    for(i=a;i<=b;i++)
        {
            (i<=9) ? printf("%s\n",name[i]):((i%2==0) ? printf("even\n"): printf("odd\n"));
        }
    return 0;
}

