# include <iostream>
using namespace std;
int main()
{
int a,b,c;
cin>>a;
cin>>b;
c=a*b;
while(a!=b)
{
if(a>b)
a=a-b;
else
b=b-a;
}
cout<< a <<endl;
cout<< c/a<<endl;
return 0;
}


