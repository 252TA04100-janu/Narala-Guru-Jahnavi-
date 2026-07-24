#include<stdio.h>
void main()
{
    int n,rem,rev=0,temp;
    printf ("enter n value");
    scanf("%d",&n);
    temp=n;
    while (n>0)
{
    rem=n%10;
    rev=rev*10+rem;
    n=n/10;
}
if(temp==rev)
{
    printf ("%d is a Palindrome",temp);
}
else
{
    printf ("%d is not a Palindrome",temp);
}
}
