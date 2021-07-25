#include<iostream>
using namespace std;
int main()
{
    cout<<"Enter the number of test cases=";
    int t;
    cin>>t;
    for(int i=0;i<t;i++)
    {
        cout<<"Enter the number of elements=";
        int n;  //Number of elements
        cin>>n;
        int a[n];
        cout<<"Enter the elements";
        for(int j=0;j<n;j++)
            cin>>a[j];   //Elements
        cout<<"Enter the key=";
        int k;
        cin>>k;//key
        int s=0;
        int e=n-1;
        int c=1;
        while(e>=s)
        {
            int mid=(s+e)/2;
            if(a[mid]==k)
            {
                cout<<"Present and No. of comparisions="<<c<<endl;
                break;
            }
            else if(a[mid]<k)
            {
             s=mid+1;
            c++;
            }
            else
            {
            e=mid-1;
            c++;
            }
        }
        if(e<s)
            cout<<"Key not present and comparisions="<<c-1<<endl;
    }
    return 0;
}
