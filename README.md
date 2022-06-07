#include<iostream>
using namespace std;

int sum(int , int);
void g(void);

int main()
{
int num1, num2;
cout<< "\n Enter num 1 : " ;
cin>>num1;
cout<< "\n Enter num 2 : " ;
cin>>num2;
cout<<"\n total sum : "<<sum(num1, num2);
g();
    return 0;
}
int sum(int a, int b)
{
    int c = a+b;
    return c;
}

void g()
{
    cout<<"\n good, morning " <<endl;
}
