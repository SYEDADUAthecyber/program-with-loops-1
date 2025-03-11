# program-with-loops-1



#include <iostream>
using namespace std;

int main() {
    int sum = 0;

    // (1) Using for loop
    for (int i = 2; i < 100; i += 3) {
        sum += i;
    }
    cout << "Sum using for loop: " << sum << endl;

    // (2) Using do-while loop
    sum = 0;
    int i = 2;
    do {
        sum += i;
        i += 3;
    } while (i < 100);
    cout << "Sum using do-while loop: " << sum << endl;

    // (3) Using while loop
    sum = 0;
    i = 2;
    while (i < 100) {
        sum += i;
        i += 3;
    }
    cout << "Sum using while loop: " << sum << endl;

    return 0;
}
