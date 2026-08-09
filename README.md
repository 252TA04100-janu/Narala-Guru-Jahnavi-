#include<stdio.h>
void main()
{
int n, i, count = 0;
printf("enter n value');
scanf("%d",&n);
for( i = 1 ; i <= n;i++)
{
if(n%i==0)
{
count+=1;
}
}
if(count==2)
{
printf("%d is prime", n);
}
else
{
printf("%d is not prime', n);
}
}
