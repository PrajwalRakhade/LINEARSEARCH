# LINEARSEARCH
HOW TO WRITE THE CODE TO  SEARCH THE ELEMENT WHICH IS PRESENT IN ARRY

#include <iostream>
using namespace std;


int linearsearch(int a[],int n,int x){
   int i;
    for (i=0;i<n;i++)
    {
        if (a[i]==x){
        return 1;
    }
    }
    return 0;
}

int main()
{
  int a[]={1,2,3,4,56,67};
   int x=56;
   int n=7;
   
   int find=linearsearch(a,n,x);
  
if (find==1){
    cout<<"found";
}
else{
    cout<<"not found";
}
   

    return 0;
}
