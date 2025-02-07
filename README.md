# Array Input and Output Demo

A simple C++ program demonstrating how to input and output elements of an array using a loop.

## Description

This program allows the user to input five integer elements into an array and then outputs each element to the console. It demonstrates basic array handling and loop operations in C++.

### Key Features
- Array input handling
- Loop-based input and output
- Basic console I/O
- Simple user interaction

## Code Structure

```cpp
#include <iostream>
using namespace std;

int main() {
    int arr[5];

    for (int i = 0; i < 5; i++) {
        cout << "Input element: ";
        cin >> arr[i];
    }

    cout << arr[0] << endl;
    cout << arr[1] << endl;
    cout << arr[2] << endl;
    cout << arr[3] << endl;
    cout << arr[4] << endl;

    return 0;
}
