# Zadacha

# КОД

#include <iostream>
using namespace std;

int main() {
    int n;
    unsigned long long fact = 1;
    
    cout << "Введите число: ";
    cin >> n;
    
    for (int i = 1; i <= n; i++)
        fact *= i;
    
    cout << "Факториал = " << fact << endl;
    return 0;
}
