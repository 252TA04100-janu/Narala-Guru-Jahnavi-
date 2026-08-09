#include <stdio.h>
void main()
{ 
int n, i=1, sum=0;
printf("enter n value");
scanf("%d", &n);
while (i<n)
if(n%i==0)
sum += i;
}
i++;
}
if (sum == n)
{
printf("%d is Pertect", n);
}
else if(sum<n)
{
printf ("%d is deficient",n);
}
else
{
printf ("%d is abondent",n);
}
}
