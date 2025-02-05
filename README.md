#include <iostream>
#include<string>
using namespace std;
int main(){
    int n;
    cin>>n;
    string s;
     cin>>s;
    int Anton=0;
    int Danik=0;
    
    for (int i=0; i<s.length(); i++){
       
        if(s[i]=='A'){
            Anton++;
        }
        else{
            Danik++;
        }
    }
    if(Anton>Danik){
        cout<<"Anton";
        
    }
    else if(Anton<Danik){
        cout<<"Danik";
    }
    else {
        cout<<"Friendship";
    }
}
