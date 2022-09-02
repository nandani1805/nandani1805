
#include <stdio.h>
int main()
{
 int a = 12;
 int b = 23;
 int c;
printf("Numbers before swapping using third variable is : %d and %d\n",a,b);
c = a;
a = b;
b = c;
printf("Numbers before swapping using third variable is : %d and %d",a,b);
}
