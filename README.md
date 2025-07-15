# Experiment-2
AIM:To study and implement C++ Program Structure (Data Types)
C++ Data Types
- int – Integer numbers (e.g., 1, -42)
- float – Floating-point numbers with decimals (e.g., 3.14)
- double – Double-precision floating-point (more accurate than float)
- char – Single character (e.g., 'A', 'z')
- bool – Boolean values (true or false)
- void – Represents "no type" (used for functions that return nothing)
Code:
#include<iostream>
#include<string>
using namespace std;
int main()
{
    int a;
    cout<<"Enter any Integer"<<endl;
    cin>>a;
    char b;
    cout<<"Enter a character"<<endl;
    cin>>b;
    float c;
    cout<<"Enter a number"<<endl;
    cin>>c;
    string d;
    cout<<"Enter a word"<<endl;
    cin>>d;
    double e;
    cout<<"Enter a big number"<<endl;
    cin>>e;
    bool f;
    cout<<"Enter 1 or 0"<<endl;
    cin>>f;
    cout<<"Float= "<<c<< " and the size is "<<sizeof(c)<<" bytes"<<endl;
    cout<<"Integer= "<<a<< " and the size is "<<sizeof(a)<<" bytes"<<endl;
    cout<<"Character= "<<b<< " and the size is "<<sizeof(b)<<" bytes"<<endl;
    cout<<"Double= "<<e<< " and the size is "<<sizeof(e)<<" bytes"<<endl;
    cout<<"String= "<<d<< " and the size is "<<sizeof(d)<<" bytes"<<endl;
    cout<<"Boolean= "<<f<< " and the size is "<<sizeof(f)<<" bytes"<<endl;
}
Output:
Enter any Integer
4
Enter a character
6
Enter a number
78
Enter a word
hello
Enter a big number
234516346
Enter 1 or 0
0
Float= 78 and the size is 4 bytes
Integer= 4 and the size is 4 bytes
Character= 6 and the size is 1 bytes
Double= 2.34516e+08 and the size is 8 bytes
String= hello and the size is 32 bytes
Boolean= 0 and the size is 1 bytes


