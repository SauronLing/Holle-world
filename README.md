# //*****ex1-1.cpp*****
This is an cpp form book c++
#include <iostream.h>
#define PI 3.14159
float sum(float x);
void main()
{
    float r,s;
    cout<<"Input r:";
    cin>>r;
    s=sum(r);
    cout<<"r="<<r<<" "<<"s="<<" "<<s<<endl;
}
float sum(float x)
{
return PI*x*x;
}
