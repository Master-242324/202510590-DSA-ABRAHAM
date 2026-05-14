@Master-242324
Master-242324
opened 2 days ago
Owner
#include
using namespace std;

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main()
{
int i,n=10,key;
int arr[10];

cout<<"enter numbers:"<<endl;
for(i=0;i<n;i++){
	
	cin>>arr[i];
  }
cout <<"enter a key"<<endl;

cin>>key;
for(i=0;i<n;i++){
		
	if(arr[i]==key){
		cout<<"the element is there"<<endl;
	break;
	}
}
return 0;

}
