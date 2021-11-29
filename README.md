# hackkerank-solution-for-loop
#include <iostream>
#include <cstdio>
using namespace std;

int main() {
    // Complete the code.
    int n;
    cout<<"enter number here";
    cin>>n;
    if(n>9 && n%2==0){
        cout<<"even";
    }else if(n>9) {
        cout<<"odd";
        
    }
    
    
    for( int i=1; i<=9; i++)
    
    {
        if (n==1)
    cout<<"one";
    else if(n==2)
    cout<<"two";
    else if(n==3)
    cout<<"three";
    else if(n==4)
    cout<<"four";
    else if(n==5)
    cout<<"five";
    else if(n==6)
    cout<<"six";
    else if(n==7)
    cout<<"seven";
    else if(n==8)
    cout<<"eight";
    else if(n==9)
    cout<<"nine";
    
    return 0;
    
    
}
}
