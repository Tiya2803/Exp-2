# Experiment-2
# Aim:
The aim of this program is to determine and print the size of various data types in bytes using the sizeof operator in C++.

# Theory:
Data Types and Variables:

Variables a, b, c, d, e, f, g, h, and i are declared to represent different data types (char, int, short int, long int, float, double, long double, bool, wchar_t respectively).

Sizeof Operator:

The sizeof operator is used to determine the size of each variable in bytes. Each size is printed using std::cout along with appropriate labels.

# Code:
```
#include <iostream>

int main() {
    char a;
    int b;
    short int c;
    long int d;
    float e;
    double f;
    long double g;
    bool h;
    wchar_t i;

    std::cout << "Size of char: " << sizeof(a) << " byte" << std::endl;
    std::cout << "Size of int: " << sizeof(b) << " bytes" << std::endl;
    std::cout << "Size of short int: " << sizeof(c) << " bytes" << std::endl;
    std::cout << "Size of long int: " << sizeof(d) << " bytes" << std::endl;
    std::cout << "Size of float: " << sizeof(e) << " bytes" << std::endl;
    std::cout << "Size of double: " << sizeof(f) << " bytes" << std::endl;
    std::cout << "Size of long double: " << sizeof(g) << " bytes" << std::endl;
    std::cout << "Size of bool: " << sizeof(h) << " byte" << std::endl;
    std::cout << "Size of wchar_t: " << sizeof(i) << " bytes" << std::endl;

    return 0;
}
```
# Conclusion:
This program effectively illustrates how to use the sizeof operator to obtain the size of various data types in bytes in C++. The sizes are printed to the console, showing the memory allocation for each type on the specific environment where the program is compiled and executed. The output confirms the standard sizes of these data types on most typical systems, providing valuable information for understanding memory usage and data representation in C++ programming.
