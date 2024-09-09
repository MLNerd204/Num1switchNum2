#include <iostream>
using namespace std;

int main(){

    int num1=2;
    int num2=1;
    
    int temp;    
    temp = num1;    
    num1=num2;
    num2=temp;
    
    cout<<"num 1 is: "<<num1<<"\n"<<"num 2 is: "<<num2;
    return 0;
}

\\ For this programming I was tasked to keep the original programming while still finding a way to have each integer have a different meaning/input. What I did was I have
inputed a new integer "temp" which has allowed me to set its input as num1 which would give the same values. With this new variable I was able to have the integer "num1" equal
to the value of "num2" establishing a new value for "num1" making it equal "1." With the value of num1 swapped I was then able to change the value of "num2" as I would establish
it to equal the value of num1 as in line 12,"num2=temp" and in line 10,"temp=num1."
