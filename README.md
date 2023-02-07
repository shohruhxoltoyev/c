#include <iostream>
using namespace std;
int main()
{
	setlocale(LC_ALL, "uzb");
	int chocolate = 2; 
	int milk = 3;
	int coffee = 1;
	float price0fChocolate = 11.04;
	float price0fMilk = 9.59;
	float price0fCoffee = 70.77;

	float sum = 0;


	sum = (chocolate * price0fChocolate) + (milk * price0fMilk) + (coffee * price0fCoffee);
	cout << "   opshi shot          =";
	cout << chocolate * price0fChocolate << '+' << milk * price0fMilk << '+' << coffee * price0fCoffee;
	cout << "=" << sum << endl << endl;
	return 0;

}
