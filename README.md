# a1_10684120.cc
c++ program that accepts user input as an integer and outputs whether or not the value supplied is prime
//Program to show whether a number is prime or not
#include<iostream>
using namespace std;
int main()

{
int n;
bool flag=false;
cout<<"Please enter a number"<<endl;
cin>>n;
for(int i=2; i<n; i++)
{if(n%i==0)
 flag=true;
  break;}
if (flag==false && n>1)
cout<<"This number is prime";
else
cout<<"This number is not prime";
return 0;
}
