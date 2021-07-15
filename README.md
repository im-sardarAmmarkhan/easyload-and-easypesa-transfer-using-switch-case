
#include<iostream>
using namespace std;
int main()
{
    int mobile;
    int amount;
	int myChoice;
	int status;
    int exit;
	cout<<"Enter your choice\npress 1 for easy load\npress 2 to for money transfer \npress 3 to check account status\npress 4 to exit";
	cin>>myChoice;
	switch(myChoice)
	{
		case 1:
		cout<<"Enter your mobile number";
		cin>>mobile;
		cout<<"Enter ammount";
		cin>>amount;
		cout<<"eassy load done";
		break;
		case 2:
		cout<<"Enter your mobile number";
		cin>>mobile;
		cout<<"Enter amount";
		cin>>amount;
		cout<<"amoount transfered";
		break;
		case 3:
		cout<<"press 3 to check status";
		cin>>status;
		cout<<"you have 100000 Rs";
		break;
		case 4:
			cout<<"press 4 to exit";
			cin>>exit;
			cout<<"exit";
		default:
		cout<<"invalid input";
	}
}
