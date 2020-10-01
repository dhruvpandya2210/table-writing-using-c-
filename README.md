# table-writing-using-c-
You can write table of any number using c code

#include<stdio.h>
#include<conio.h>

Void main ()
{
    Int i,n,x;
    Clrscr();
    Printf("enter your number:");
    Scanf("%d",&n)
    For(i=1;i<5;i++)
    {
      x=n*i;
      printf("%d%d%d",n,i,x);
    }
    getch();
}
