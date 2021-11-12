# Cubes
#for loop
#include<iostream>
using namespace std;
int main()
{
	int n,cube;  //declaring variable with datatype integer
	cout << "Enter an integer: " << endl;
	cin >> n;
	for (int k = 1; k <= n; k++)  //using for loop
	{
		cube = k * k * k;    //formula to calculate cube of an integer
		cout << "Number is: " << k << " and the cube is : " << cube << endl;
	}
	return 0;
}
