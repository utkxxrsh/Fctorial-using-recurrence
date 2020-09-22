# Fctorial-using-recurrence
#include <bits/stdc++.h>

using namespace std;


int factorial(int n) {
   int p=1;
   for(int i=1;i<=n;i++){
       p=p*i;
   }
   return p;
}
int main(){
    int n1;
    cin>>n1;
    int z=factorial(n1);
    cout<<z;
}

