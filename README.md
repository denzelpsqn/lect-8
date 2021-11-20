# lect-8

#include <iostream>
using namespace std;

int main()
{
	int month;
	//user input
	cout << "Enter a number ( 1-12 ):; ";
	cin >> month;
	cout << " " << endl;
	//switch statement
	switch (month) {
	case 1:
		cout << "1 = January, 31" << endl;
		break;
	case 2:
		cout << "2 = February, 28" << endl;
		break;
	case 3:
		cout << "3 = March, 31" << endl;
		break;
	case 4:
		cout << "4 = April, 30" << endl;
		break;
	case 5:
		cout << "5 = May, 31" << endl;
		break;
	case 6:
		cout << "6 = June, 30" << endl;
		break;
	case 7:
		cout << "7 = July, 31" << endl;
		break;
	case 8:
		cout << "8 = August, 30" << endl;
		break;
	case 9:
		cout << "9 = September, 30" << endl;
		break;
	case 10:
		cout << "10 = October, 31" << endl;
		break;
	case 11:
		cout << "11 = November, 30" << endl;
		break;
	case 12:
		cout << "12 = December, 31" << endl;
		break;
	default:
		cout << "Invalid!" << endl;

	}
	cin.get();
	return 0;
}
