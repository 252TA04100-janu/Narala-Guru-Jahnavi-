#include <stdio.h>
Void main()
{
int sum=0,n,i=1;
printf ("enter n value");
scanf("%d", &n);
while (i < n)
{
if( n%10 ==0)
{
sum += i
}
i++;
}
if( sum ==n)
printf("%d is Perfect", n);
}
else
{
printf("%d is not Pertect", n);
}
}
