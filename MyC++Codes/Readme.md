#include <conio.h>
#include <iostream>
using namespace std;
int main(){
    int iRange,iuser_input,iMaximum=0;
    cout<<"Enter the no of input want to test for: ";
    cin>>iRange;
    for (int Iincrement=1;iRange>=Iincrement;Iincrement++){
        cout<<"Enter the value for "<<Iincrement<<": ";
        cin>>iuser_input;
        if (iuser_input>iMaximum){
            iMaximum=iuser_input;
        }
    }
    cout<<"Maximumest number u entered is "<<iMaximum;
    return iMaximum;
}
