#include<iostream>
using namespace std;

int main(){
    int a,b,c;
    cin>>a>>b>>c;
    int w=a+b+c;
    
    if(w>100){
        cout<<"Eorror";
    }
    else if(w>=80){
        cout<<"A";
    }
    else if(w>=75){
        cout<<"B+";
    }
    else if(w>=70){
        cout<<"B";
    }
    else if(w>=65){
        cout<<"C+";
    }
    else if(w>=60){
        cout<<"C";
    }
    else if(w>=55){
        cout<<"D+";
    }
    else if(w>=50){
        cout<<"D";
    }
    else{
        cout<<"F";
    }
    return 0;
}


