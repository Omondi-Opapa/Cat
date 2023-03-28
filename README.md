# Simple Calculator
#include <iostream>

using namespace std;

int main()
{
    int a;
    int b;
    int sum;
    int difference;
    cout << "Enter a number" << endl;
    cin >> a;
    cout << " Enter another number \n" ;
    cin >> b;

    sum = a+b;
    cout <<"The sum of those numbers is " << sum << endl;

    difference = a-b;
    cout << "The difference of those numbers is " << difference << endl;
    return 0;
}
