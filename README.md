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
