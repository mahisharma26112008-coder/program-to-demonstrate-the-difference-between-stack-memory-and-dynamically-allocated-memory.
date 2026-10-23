# program-to-demonstrate-the-difference-between-stack-memory-and-dynamically-allocated-memory.

#include<iostream>
 using namespace std;
int main(){
  int a=10;

int *p=new int;
*p=20;

cout<<"static memory : "<<a<<"\n";
cout<<"dynamic memory : "<<*p<<"\n";

return 0;

}
