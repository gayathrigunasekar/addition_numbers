# addition_numbers
addition of two numbers using pointers in c
#include<iostream.h>
#include<conio.h>
Void main()
{
 Int f,s,*p,*q,sum;
 cout<<"enter two integers to add\n";
 cin>>f>>s;
 p=&f;
 q=&s;
 sum=*p+*q;
 cout<<"sum of two numbers="<<sum;
 getch();
}
