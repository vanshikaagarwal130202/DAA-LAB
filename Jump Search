#include<iostream>
#include<math.h>
using namespace std;
int main()
{
    cout<<"Enter the number of test cases="<<endl;
    int t;
    cin>>t;
    for(int i=0;i<t;i++)
    {
    cout<<"Enter the number of elements="<<endl;
    int n;
    cin>>n;
    int a[n];
    cout<<"Enter array elements="<<endl;
    for(int j=0;j<n;j++)
    {
        cin>>a[j];
    }
    cout<<"Enter key="<<endl;
    int key;
    cin>>key;
    int step=sqrt(n);
    int s=0;
    int e=s+step;
    int c=1;
    while(a[e]<key)
    {
        c++;
        s=e;
        e=e+step;
        if(e>n-1)
        {
        e=n-1;
        break;
        }
    }
    int k;
    for(k=s+1;k<=e;k++)
    {
        c++;
        if(a[k]==key)
        {
        cout<<"Present and number of comparisions="<<c<<endl;
        break;
        }
    }

if(k==e+1)
cout<<"Not present"<<endl;
}
return 0;
}
