# calcu-later
```cpp
#include <iostream>
int main() {
    int number1;
    int number2;
    char operation;
    char userchoice;
    char y;
    char n;
    do {    std::cout << (" pick a number: ");
    std::cin >> (number1);
    std::cout << (" pick a second number: ");
    std::cin >> (number2);
    std::cout << " + , - , *, /";
    std::cin >> (operation);
    if (operation == '+') {
       std::cout << (number1 + number2); }
    else if (operation == '-') {
        std::cout << (number1 - number2); }
    else if (operation == '*') {
        std::cout << (number1 * number2); }
    else if (operation == '/') {
        std::cout << (number1 / number2); }
    else
    std::cout << (" invalid!! "); 
    
    std::cout << " — do you wanna continue this program? ";
    std::cin >> userchoice;
    
    } while (userchoice == 'y'); 
    std::cout << " goodbye! "; 
}
