🧮 Mini Calculator in C++
A simple interactive command-line calculator built in C++.
Great as a first C++ project — clean, readable, and covers core concepts.

---

## 💡 Features

- Addition, Subtraction, Multiplication, Division
- Handles decimal numbers (e.g. 3.5 + 2.1)
- Division by zero protection
- Clean error messages for invalid input


🚀 How to Compile & Run
On Linux / Mac
bashg++ main.cpp -o calculator
./calculator
```

### On Windows (with MinGW)
```bash
g++ main.cpp -o calculator.exe
calculator.exe
```

---

## 🖥️ Example Usage

🖥️ Example Usage
===== Mini Calculator =====
Enter first number: 10
Enter operator (+, -, *, /): /
Enter second number: 2
Result: 10 / 2 = 5
```

```
===== Mini Calculator =====
Enter first number: 5
Enter operator (+, -, *, /): /
Enter second number: 0
Error: Division by zero!
```

---

## 📁 Project Structure

📁 Project Structure
mini-calculator/
├── main.cpp       # Main source code
├── README.md      # This file
└── .gitignore     # Ignores compiled output files

🧠 Concepts Used
ConceptWhereFunctionsadd(), subtract(), multiply(), divide()double typeHandles decimal numberschar typeStores the operator characterswitch statementSelects the right operationcin / coutUser input and outputError handlingDivision by zero check

🛠️ Requirements

A C++ compiler — g++ recommended
C++11 or later (default on most systems)


🔮 Possible Improvements

Add a loop so the user can calculate multiple times
Add calculation history
Support for more operations (power, square root)
Build a graphical UI


👤 Author
Your Name
GitHub: @afrabouzehar

📄 License
This project is open source and available under the MIT License.