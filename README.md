#include <iostream>
using namespace std;
int main ()
{
	double miles = 0, gal= 0, total= 0;
	 cout<<"Enter the miles traveled on this trip"<<endl;
	 cin>> miles;
     cout<<"Enter the number of gallons used"<<endl;
     cin>> gal;
     total= miles / gal;
     cout<< "The number of miles per gallon acheived by the car is: "<<total;

	
	return 0;
}
