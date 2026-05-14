// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;
int main() {
    int high=0;
    int low=0;
    int i,n=5;
    string name[5];
    string key;
    int age[5];
    
    cout<<"Enter names:"<<endl;
    for(i=0;i<n;i++){
        cin>>name[i];
    }
    cout<<"Enter ages:"<<endl;
    for(i=0;i<n;i++){
        cin>>age[i];
    }
    cout<<"Enter key name"<<endl;
    cin>>key;
    int mid=(low+high)/2;
    for (i=0;i<n;i++){
        if(key==name[i]){
            cout<<name[i]<<age[i]<<endl;
            break;
        }
        else if(key>name[mid]){
            low=mid;
    }
    else{
        high=mid-1;
    }
    }
    return 0;
}
