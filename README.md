# Series-and-sum-together
Series of decimal number and the sum in the same line
#include <iostream>
using namespace std;

int main() {
    float i,sum=0;
    int n;
    cout<<"How long the series?= ";
    cin>>n;
    for(i=1.5;i<n+.5;i++){
        cout<<i<<"+";
        sum = sum+i;
    }
    cout<<n+.5<<"="<<sum+n+.5;
    

    return 0;
}
