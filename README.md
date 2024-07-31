# Experiment---5


Aim -> To study and implement C++ decision making statements. <br> 

Software -> Visual Studio Code <br> 

Theory -> <br> 

Code: <br> 

(A) <br> 
```

#include<iostream>
using namespace std;

int main() {
    int  n1;
    cout<<"Enter a positive number: ";   //Output - Enter a positive number: 20
    cin>>n1;
    if(n1==0) {
        cout<<n1<<" is zero."<<endl;
    }
    else if(n1%2!=0){
        cout<<n1<<" is odd."<<endl;
    }
    else {
        cout<<n1<<" is even."<<endl;        //98 is even.
    }
}
```

(B) <br> 
```
#include<iostream>
using namespace std;
int main(){
    int  n1, n2, n3;
    cout<<"Enter number-1: ";
    cin>>n1;
    cout<<"Enter number-2: ";
    cin>>n2;
    cout<<"Enter number-3: ";
    cin>>n3;

    if(n1>n2) {
        if(n1>n3) {
            cout<<n1<<" is the greatest number"<<endl;
        }
        else {
            cout<<n3<<" is the greatest number"<<endl;
        }
    }
    else if(n2>n1) {
        if(n2>n3) {
            cout<<n2<<" is the greatest number"<<endl;
        }
        else {
            cout<<n3<<" is the greatest number"<<endl;
        }
    }
    else {
        cout<<"All three numbers are equal";
    }
}
```

(C) <br> 
```
