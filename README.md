---

# 🧪 Experiment 1: Basic C++ Programs

### (Q1: Hello World & Q2: Calculator)

---

## ✅ Q1: Hello World

---

### 🎯 Aim:

To write a simple C++ program that prints **"Hello, World!"** on the screen.

---

### 📚 Theory:

The "Hello, World!" program is often the first program written when learning a new programming language.
In C++, this program helps us:

* Understand the structure of a basic C++ program.
* Learn the use of `#include` directives.
* Understand the use of `main()` function.
* Use `cout` to print output on the console.

It verifies that the development environment is set up properly.

---

### 🧠 Logic:

1. Include the iostream header file to enable input/output operations.
2. Define the `main()` function.
3. Use `cout` to display "Hello, World!".
4. Return 0 to indicate successful program termination.

---

### 🧾 Code:

```cpp
// Q1: Hello World Program in C++
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, World!";
    return 0;
}
```

---

### ✅ Output:

```
Hello, World!
```

---

### 📌 Conclusion:

The program successfully displays the message **"Hello, World!"**, demonstrating the basic structure of a C++ program and confirming that the compiler and IDE are functioning correctly.

---

## ✅ Q2: Calculator (Addition, Subtraction, Multiplication, Division)

---

### 🎯 Aim:

To write a C++ program that takes two numbers as input from the user and performs basic arithmetic operations:

* Addition
* Subtraction
* Multiplication
* Division

---

### 📚 Theory:

A calculator program is a beginner-level program that demonstrates:

* Taking user input using `cin`.
* Performing arithmetic operations using operators (`+`, `-`, `*`, `/`).
* Displaying output using `cout`.
* Handling basic runtime errors like division by zero.

This program builds problem-solving skills and reinforces understanding of data types and operators.

---

### 🧠 Logic:

1. Prompt the user to input two numbers.
2. Store the inputs in variables (`num1` and `num2`).
3. Use arithmetic operators:

   * `+` for addition
   * `-` for subtraction
   * `*` for multiplication
   * `/` for division
4. Before dividing, check if the second number is zero.
5. Display the results of each operation using `cout`.

---

### 🧾 Code:

```cpp
// Q2: Calculator Program in C++
#include <iostream>
using namespace std;

int main() {
    float num1, num2;

    // Input
    cout << "Enter first number: ";
    cin >> num1;

    cout << "Enter second number: ";
    cin >> num2;

    // Addition
    cout << "Addition: " << (num1 + num2) << endl;

    // Subtraction
    cout << "Subtraction: " << (num1 - num2) << endl;

    // Multiplication
    cout << "Multiplication: " << (num1 * num2) << endl;

    // Division
    if (num2 != 0) {
        cout << "Division: " << (num1 / num2) << endl;
    } else {
        cout << "Division: Error! Cannot divide by zero." << endl;
    }

    return 0;
}
```

---

### ✅ Sample Output:

```
Enter first number: 10
Enter second number: 5
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2
```

---

### 📌 Conclusion:

The calculator program performs all four basic arithmetic operations successfully. The program also includes a condition to prevent division by zero, which improves its reliability and robustness.

---


