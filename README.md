//# ACTIVITY-2
#include <iostream>
#include <string>
using namespace std;

int main() {
    // Declare variables to store user input
    string fullName, courseYrSec, birthday, motto;

    // Input data
    cout << "Enter your full name: ";
    getline(cin, fullName);

    cout << "Enter your course, year, and section: ";
    getline(cin, courseYrSec);

    cout << "Enter your birthday: ";
    getline(cin, birthday);

    cout << "Enter your motto/motivation in life: ";
    getline(cin, motto);

    // Output the expected result
    cout << "Hi! I am " << fullName << " of " << courseYrSec << ". Welcome to Data Structures and Algorithm!" << endl;
    cout << "My Birthday is on " << birthday << " and my motto/motivation in life is " << motto << "." << endl;

    return 0;
}
