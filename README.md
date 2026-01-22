# Create-a-class-FIB-with-construction-destruction-
#include<iostream.h>
#include<conio.h>
class fib{
public:
fib(){
cout<<"object is born\n";
}
void genfib(){
int a=0,b=1,c,1;
cout<<"Fibonacci series (first 10 terms):\n";
cout<<a<<""<<b<<"";
for(1=3;1<=0;1++){
c=a+b;
cout<<c<<"";
a=b;
b=c;
}
cout<<"\n";
}
~fib(){
cout<<"object are destroyed..\n";
}
};
void main(){
clrscr();
fib f:
f.genfib();
getch();
}
