# Experiment---5


### Aim 
To study and implement C++ decision making statements. <br> 

### Software 
Visual Studio Code <br> 

### Theory 
Decision making statements in C++ are the conditional statements that are used to execute codes based on some given conditions. <br>  
          The following are certain decsion making statements in C++ : <br> 
          1. if statement <br> 
          2.if-else statement <br> 
          3. switch statement <br> 
          4. nested if statements <br> 
          5. nested switch statements <br> 
          
### Code: <br> 

(A) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 5(A) 

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
// NAME - SHLOKA PATEL 
// PRN - 23070123120
// EXPERIMENT - 5(B)

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
// NAME- SHLOKA PATEL
// PRN -23070123120 
// EXPERIMENT - 5(C)

#include<iostream>
using namespace std;

int main() {
    int choice;
    cout<<"1) Monday"<<"\n"<<"2) Tuesday"<<"\n"<<"3) Wednesday"<<"\n"<<"4) Thursday"<<"\n"<<"5) Friday"<<"\n"<<"6) Saturday"<<"\n"<<"7) Sunday"<<"\n";
    cout<<"Enter a choice: ";
    cin>>choice;
    switch(choice) {
        case 1:
        cout<<"Monday";
        break;
        case 2:
        cout<<"Tuesday";
        break;
        case 3:
        cout<<"Wednesday";
        break;
        case 4:
        cout<<"Thrsday";
        break;
        case 5:
        cout<<"Friday";
        break;
        case 6:
        cout<<"Saturday";
        break;
        case 7:
        cout<<"Sunday";
        break;
        default:
        cout<<"Wrong Input";
    }
}
```

(D) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 5(D) 

#include<iostream>
using namespace std;

int main() {
    char oper;
    float num1, num2;
    

    cout<<"Enter an operator (+, -, *, /): ";
    cin>>oper;
    cout<<"Enter two numbers: "<<"\n";
    cin>>num1>>num2;
    switch(oper) {
        case '+':
        cout<<num1<<"+"<<num2<<"="<<num1+num2<<"\n";
        break;
        case '-':
        cout<<num1<<"-"<<num2<<"="<<num1-num2<<"\n";
        break;
        case '*':
        cout<<num1<<"*"<<num2<<"="<<num1*num2<<"\n";
        break;
        case '/':
        if (num2!=0)
        cout<<num1<<"/"<<num2<<"="<<num1/num2<<"\n";
        else
        cout<<"Error! Division by zero."<<"\n";
        break;
        default:
        cout<<"Error! The operator is not correct."<<"\n";
        break;
    }
}
```

(E) <br> 
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 5(E)    

#include <iostream>
using namespace std;
int main()
 {
int day = 1;
  switch (day) {
    case 6:
cout<< "Today is Saturday";
      break;
    case 7:
cout<< "Today is Sunday";
      break;
    default:
cout<< "Looking forward to the Weekend";
  }
  return 0;
  }
```

### Output: <br> 

(A) <br> 
![](https://github.com/Shloka-Patel/Experiment---5/blob/main/Output_5A.png)

(B)<br> 
![](https://github.com/Shloka-Patel/Experiment---5/blob/main/Output_5B.png)

(C) <br>
![](https://github.com/Shloka-Patel/Experiment---5/blob/main/Output_5C.png)

(D) <br>
![](https://github.com/Shloka-Patel/Experiment---5/blob/main/Output_5D.png)

(E) <br> 
![](https://github.com/Shloka-Patel/Experiment---5/blob/main/Output_5E.png)

### Conclusion 
I learnt about the different decion maing statements of C++ and performed tasks based on those conditions. 
