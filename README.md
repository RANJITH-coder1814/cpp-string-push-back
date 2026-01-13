# cpp-string-push-back
This program appends a single character to an existing C++ string using the `push_back()` method and prints the updated string.
# cpp-string-push_back

A simple C++ program that demonstrates how to use the `string::push_back()` function to add a character at the end of a string.

---

## 📌 Program Description

This program appends a single character to an existing C++ string using the `push_back()` method and prints the updated string.

---

## 🧠 Concepts Used

- C++ strings
- `string::push_back()` function
- Basic input/output using `cout`

---

## 🧾 Code Example

```cpp
#include<iostream>
using namespace std;

int main(){
    string s = "ranjith";
    s.push_back('R');
    cout << s << endl;
}

