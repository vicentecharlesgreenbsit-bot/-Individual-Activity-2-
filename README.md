# -Individual-Activity-2-

#include <iostream>
#include <string>
using namespace std;

int main() {
    string fullName;
    string courseYearSection;
    string birthday;
    string motto;

    
    cout << "Full name: ";
    getline(cin, fullName);

    cout << "Course, Yr. & Sec.: ";
    getline(cin, courseYearSection);

    cout << "Birthday: ";
    getline(cin, birthday);

    cout << "Motto/Motivation in Life: ";
    getline(cin, motto);

    
    cout << "Hi! I'm " << fullName << " of " << courseYearSection << ". Welcome to Data Structures and Algorithm!" << endl;
    cout << "My Birthday is on " << birthday << ". and my motto/motivation in life is " << motto << endl;

    return 0;
}
