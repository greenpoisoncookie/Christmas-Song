# Christmas-Song
This project is written with C++ and counts down the twelve days of Christmas depending on user selection.
//Program: ChristmasAllisonBarnes (Final Performance Program)
//Programmer: Allison Barnes
//Date: 12/5/2016
//This program will display the options for the twelve days of Christmas, and will ask for a user input. The user will put in which number they want to pick from 1-12, and the associated number with the line from the Christmas song will display on screen. If a number outside of 1 - 12 is picked, there will be an error message pop up.

#include <iostream>
#include <cmath>
using namespace std;

int main()
{
	int day			= 0;

　
	//begin output of list to screen
	cout << "\t\t\tThe Twelve Days of Christmas" << endl << endl;
	cout << "\t 1: Partridge in a Pear Tree." << endl;
	cout << "\t 2: Turtle Doves." << endl;
	cout << "\t 3: French Hens." << endl;
	cout << "\t 4: Calling Birds." << endl;
	cout << "\t 5: Golden Rings." << endl;
	cout << "\t 6: Geese a Laying." << endl;
	cout << "\t 7: Swans a Swimming." << endl;
	cout << "\t 8: Maids a Milking." << endl;
	cout << "\t 9: Ladies Dancing. " << endl;
	cout << "\t 10: Lords a Leaping." << endl;
	cout << "\t 11: Pipers Piping." << endl;
	cout << "\t 12: Drummers Drumming." << endl << endl;

　
//begin a while loop
	while(day != -1)
	{
		cout << "\tEnter the day (1 through 12 to start, -1 to stop): ";
		cin >> day;
	//begin case for options selected
		switch (day)
		{
		case 1:
			cout << "\n\t\t 1: Partridge in a Pear Tree." << endl << endl;
			break;
		case 2:
			cout << "\n\t\t 2: Turtle Doves." << endl << endl;
			break;
		case 3:
			cout << "\n\t\t 3: French Hens." << endl << endl;
			break;
		case 4:
			cout << "\n\t\t 4: Calling Birds." << endl << endl;
			break;
		case 5:
			cout << "\n\t\t 5: Golden Rings." << endl << endl;
			break;
		case 6:
			cout << "\n\t\t 6: Geese a Laying." << endl << endl;
			break;
		case 7:
			cout << "\n\t\t 7: Swans a Swimming." << endl << endl;
			break;
		case 8:
			cout << "\n\t\t 8: Maids a Milking." << endl << endl;
			break;
		case 9:
			cout << "\n\t\t 9: Ladies Dancing. " << endl << endl;
			break;
		case 10:
			cout << "\n\t\t 10: Lords a Leaping." << endl << endl;
			break;
		case 11:
			cout << "\n\t\t 11: Pipers Piping." << endl << endl;
			break;
		case 12:
			cout << "\n\t\t 12: Drummers Drumming." << endl << endl;
			break;
		default:
			if (day > 12 || day < 0)
			cout << "\n\t Error! Please enter a number between 1-12 for your gift." << endl << endl;
		}//endcase

	}//endwhile	

	system("pause");
	return 0;

}
