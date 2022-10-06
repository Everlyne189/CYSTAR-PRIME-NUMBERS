#include <iostream>
using namespace std;
int main()
{
int lower, higher, flag, temporary;
cout << "Please enter the two numbers for finding prime numbers between them: "<< endl;
cin >> lower >> higher;
if ( lower > higher) {    //It will swap the numbers if lower number is greater than higher number.
temporary = lower;
lower = higher;
higher = temporary;
}
cout << "Hence the Prime numbers between the number " << lower << " and " << higher << " are: "<< endl;
while ( lower < higher)
{
flag = 0;
for ( int x = 2; x <= lower/2; ++x)
{
if ( lower % x == 0)
{
flag = 1;
break;
}
}
if ( flag == 0)
cout << lower << " ";
++lower;
}
return 0;
}
