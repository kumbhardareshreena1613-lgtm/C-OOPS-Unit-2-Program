# Object-Oriented Programming with C++ (OOPs)

### Student Details
- **Student Name:** Shreena Kumbhardare
- **PRN:** AD2623
- **Class & Div:** SY-F
- **Programme:** S.Y. B.Tech. Artificial Intelligence and Data Science
- **Course:** Object-Oriented Programming with C++
- **Course Code:** ADPC303
- **Semester:** III
- **Language Standard:** C++17 or later

---

## Repository Structure

```text
C-OOPS-Unit-2-Program/
├── unit1/               # Unit 1: Basics of C++ and Object-Oriented Concepts
│   ├── Program_01.cpp
│   ├── Program_02.cpp
│   ├── ...
│   └── Program_08.cpp
├── unit2/               # Unit 2: Inheritance Practical Code Book
│   ├── Program_01.cpp
│   ├── Program_02.cpp
│   ├── ...
│   └── Program_16.cpp
├── unit3/               # Unit 3: Polymorphism Practical Code Book
│   ├── Program_01.cpp
│   ├── Program_02.cpp
│   ├── ...
│   └── Program_16.cpp
└── README.md
```

---

## Unit 1: Basics of C++ and Object-Oriented Programming

| Sr. No. | Program Title | Main Concept | Source Code |
| :---: | :--- | :--- | :---: |
| 1 | Basic Data Types | Store student roll number, grade, and fee amount | [Program_01.cpp](unit1/Program_01.cpp) |
| 2 | if-else | Check whether a student has passed or failed | [Program_02.cpp](unit1/Program_02.cpp) |
| 3 | Loop and Array | Print marks of five students | [Program_03.cpp](unit1/Program_03.cpp) |
| 4 | Functions | Create an addition function for reuse | [Program_04.cpp](unit1/Program_04.cpp) |
| 5 | Class and Object | Store student details using class and object | [Program_05.cpp](unit1/Program_05.cpp) |
| 6 | Constructor and Destructor | Show automatic object initialization and cleanup | [Program_06.cpp](unit1/Program_06.cpp) |
| 7 | Static Member | Count how many objects are created | [Program_07.cpp](unit1/Program_07.cpp) |
| 8 | Inline and Friend Function | Access private data using inline getter and friend function | [Program_08.cpp](unit1/Program_08.cpp) |

---

## Unit 2: Inheritance — Practical Code Book

| Sr. No. | Title | Main Concept | Source Code |
| :---: | :--- | :--- | :---: |
| 1 | Basic single inheritance | Base and derived classes | [Program_01.cpp](unit2/Program_01.cpp) |
| 2 | Protected member access | protected access specifier | [Program_02.cpp](unit2/Program_02.cpp) |
| 3 | Public versus private inheritance | Inheritance modes | [Program_03.cpp](unit2/Program_03.cpp) |
| 4 | Multilevel inheritance | Three-level hierarchy | [Program_04.cpp](unit2/Program_04.cpp) |
| 5 | Hierarchical inheritance | One base, multiple derived classes | [Program_05.cpp](unit2/Program_05.cpp) |
| 6 | Multiple inheritance | Two base classes | [Program_06.cpp](unit2/Program_06.cpp) |
| 7 | Multiple-inheritance ambiguity | Scope-resolution operator | [Program_07.cpp](unit2/Program_07.cpp) |
| 8 | Constructor and destructor order | Object lifecycle | [Program_08.cpp](unit2/Program_08.cpp) |
| 9 | Parameterized base constructor | Initializer list | [Program_09.cpp](unit2/Program_09.cpp) |
| 10 | Function overriding | virtual and override | [Program_10.cpp](unit2/Program_10.cpp) |
| 11 | Abstract class | Pure virtual function | [Program_11.cpp](unit2/Program_11.cpp) |
| 12 | Virtual base class | Diamond inheritance | [Program_12.cpp](unit2/Program_12.cpp) |
| 13 | Friend class | Special access permission | [Program_13.cpp](unit2/Program_13.cpp) |
| 14 | Nested class | Class inside another class | [Program_14.cpp](unit2/Program_14.cpp) |
| 15 | Mini-project: Vehicle rental | Integrated inheritance | [Program_15.cpp](unit2/Program_15.cpp) |
| 16 | Mini-project: Employee payroll | Abstract base and overriding | [Program_16.cpp](unit2/Program_16.cpp) |

---

## Unit 3: Polymorphism — Detailed Practical Code Book

| Sr. No. | Program Title | Main Concept | Source Code |
| :---: | :--- | :--- | :---: |
| 1 | Function overloading | Compile-time polymorphism | [Program_01.cpp](unit3/Program_01.cpp) |
| 2 | Area calculator | Function overloading with different parameters | [Program_02.cpp](unit3/Program_02.cpp) |
| 3 | Unary minus operator | Unary operator overloading | [Program_03.cpp](unit3/Program_03.cpp) |
| 4 | Prefix and postfix increment | Unary operator overloading | [Program_04.cpp](unit3/Program_04.cpp) |
| 5 | Complex number addition | Binary + operator overloading | [Program_05.cpp](unit3/Program_05.cpp) |
| 6 | Distance comparison | Relational operator overloading | [Program_06.cpp](unit3/Program_06.cpp) |
| 7 | Non-member/friend operator | Operator overloading using friend function | [Program_07.cpp](unit3/Program_07.cpp) |
| 8 | Base pointer without virtual function | Static binding demonstration | [Program_08.cpp](unit3/Program_08.cpp) |
| 9 | Base pointer with virtual function | Run-time polymorphism | [Program_09.cpp](unit3/Program_09.cpp) |
| 10 | Base reference with virtual function | Dynamic binding through references | [Program_10.cpp](unit3/Program_10.cpp) |
| 11 | Abstract class | Pure virtual function | [Program_11.cpp](unit3/Program_11.cpp) |
| 12 | Collection of shape pointers | Polymorphic processing | [Program_12.cpp](unit3/Program_12.cpp) |
| 13 | Virtual destructor | Safe deletion through base pointer | [Program_13.cpp](unit3/Program_13.cpp) |
| 14 | Object slicing | Why references/pointers are needed | [Program_14.cpp](unit3/Program_14.cpp) |
| 15 | Payment system | Abstract interface and real-world example | [Program_15.cpp](unit3/Program_15.cpp) |
| 16 | Payroll mini-project | Integrated polymorphism application | [Program_16.cpp](unit3/Program_16.cpp) |

---

## Compilation & Execution Guide

### Linux / macOS
```bash
g++ -std=c++17 filename.cpp -o program
./program
```

### Windows (MinGW)
```cmd
g++ -std=c++17 filename.cpp -o program.exe
program.exe
```