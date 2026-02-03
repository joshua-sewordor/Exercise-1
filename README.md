#include <iostream>
using namespace std;

int main() {
    int secretNumber = 7;   // secret number (hardcoded)
    int guess;

    cout << "Welcome to the Number Guessing Game!" << endl;

    while (true) {
        cout << "Enter your guess: ";
        cin >> guess;

        if (guess > secretNumber) {
            cout << "Too High" << endl;
        } else if (guess < secretNumber) {
            cout << "Too Low" << endl;
        } else {
            cout << "Correct! You guessed the number." << endl;
            break;
        }
    }

    return 0;
}
