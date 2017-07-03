#include<iostream>
using namespace std;
int main()
{
int n,i;
bool isprime=true;
cout<<"enter n value:"<<endl;
cin>>n;
for(i=2;i<=n/2;++i)
{
if(n%2==0)
{
isprime=false;
break;
}
}
if(isprime)
cout<<"this is prime num";
else
cout<<"this is not prime";
}
