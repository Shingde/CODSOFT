#include <iostream>
#include <cstdlib>
#include <ctime>

int main() {
    
    srand(time(nullptr));

    std::cout << "Welcome to the Guess the Number game!\n";
    
    int secretNumber = rand() % 100 + 1;
    int guess;

    std::cout << "I've picked a number between 0 t0 100, Can you guess what it is?\n";
    
    do {
        std::cout << "Enter your guess: ";
        std::cin >> guess;

        if (guess > secretNumber) {
            std::cout << "Too high! Try again.\n";
        } else if (guess < secretNumber) {
            std::cout << "Too low! Try again.\n";
        } else {
            std::cout << "Congratulations! You guessed the correct number.\n";
        }
    } while (guess != secretNumber);

    return 0;
}
