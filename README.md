#include <stdio.h> 
#include<math.h>
void main()
int n, n1, temp, l= 0 ,rem, sum = 0;
printf("enter n value");
scanf("%d", &n);
n1=n;
temp=n;
while(n>0)
{
l+=1;
n = n / 10;
}
while(n1> 0)
{
rem = n1 %10;
sum = sum + pow (rem, l);
n1=n1/10;
}
if(temp==sum)
{
printf('%d is armstrong", temp);
}
else
{
printf("%d is not armstrong", temp);
}
}
