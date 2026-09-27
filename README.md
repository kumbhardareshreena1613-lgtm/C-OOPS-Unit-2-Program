# OOP C++ Programming Activity

## Student Details
- **Student Name:** Shreena Kumbhardare
- **PRN:** AD2623
- **Class/Division:** Sy-F
- **Course Name:** Object-Oriented Programming (OOP)
- **Course Code:** ADPC303

---

## Units Covered
1. **Unit I — C++ Basics & Core OOP** (`unit1/`)
2. **Unit II — Inheritance** (`unit2/`)
3. **Unit III — Polymorphism** (`unit3/`)

---

## Unit I: C++ Basics & Core OOP

### List of Programs

| # | Title | Folder | Main Concept | Description |
|---|-------|--------|--------------|-------------|
| 1 | Basic Data Types | [`unit1/Program_01.cpp`](unit1/Program_01.cpp) | Fundamental Data Types | Demonstrates basic data types (`int`, `char`, `float`) and standard stream I/O. |
| 2 | Conditional Statements (if-else) | [`unit1/Program_02.cpp`](unit1/Program_02.cpp) | Selection Control Structure | Checks pass/fail criteria using condition checking with `if-else`. |
| 3 | Loops and Arrays | [`unit1/Program_03.cpp`](unit1/Program_03.cpp) | Arrays and Iteration | Demonstrates 1D array traversal using a standard `for` loop. |
| 4 | User-Defined Functions | [`unit1/Program_04.cpp`](unit1/Program_04.cpp) | Modular Functions | Demonstrates function prototyping, parameter passing by value, and return values. |
| 5 | Classes and Objects | [`unit1/Program_05.cpp`](unit1/Program_05.cpp) | Class & Object Basics | Encapsulates student data and behaviors into a class with object instances. |
| 6 | Constructor and Destructor | [`unit1/Program_06.cpp`](unit1/Program_06.cpp) | Object Lifecycle | Demonstrates automatic initialization via constructor and cleanup via destructor. |
| 7 | Static Data Members | [`unit1/Program_07.cpp`](unit1/Program_07.cpp) | Static Class Members | Tracks total object creations using a shared class-level static counter. |
| 8 | Inline and Friend Functions | [`unit1/Program_08.cpp`](unit1/Program_08.cpp) | Inline & Friend Functions | Accesses private members via an inline getter and a non-member friend function. |


## Unit II: Inheritance

### List of Programs

| # | Title | Folder | Description |
|---|-------|--------|-------------|
| 1 | Basic Single Inheritance | [`unit2/Program_01.cpp`](unit2/Program_01.cpp) | A `Person` base class is extended by a `Student` derived class, which adds a roll number and displays both name and roll number. |
| 2 | Protected Member Access | [`unit2/Program_02.cpp`](unit2/Program_02.cpp) | An `Employee` base class exposes a protected `name` member which a `Developer` derived class accesses directly to display employee and language details. |
| 3 | Public versus Private Inheritance | [`unit2/Program_03.cpp`](unit2/Program_03.cpp) | Shows how `Base::show()` remains publicly accessible through public inheritance but becomes inaccessible from outside the class through private inheritance. |
| 4 | Multilevel Inheritance | [`unit2/Program_04.cpp`](unit2/Program_04.cpp) | Demonstrates a three-level chain `Person -> Employee -> Manager`, where `Manager` displays data inherited from both its parent and grandparent classes. |
| 5 | Hierarchical Inheritance | [`unit2/Program_05.cpp`](unit2/Program_05.cpp) | A single `Vehicle` base class is inherited by two separate derived classes, `Car` and `Bike`, each adding its own specific behaviour. |
| 6 | Multiple Inheritance | [`unit2/Program_06.cpp`](unit2/Program_06.cpp) | A `Student` class inherits from two base classes, `Academic` and `Sports`, and combines marks from both to compute a total. |
| 7 | Resolving Multiple-Inheritance Ambiguity | [`unit2/Program_07.cpp`](unit2/Program_07.cpp) | `Academic` and `Sports` both define a `display()` function; the scope resolution operator (`::`) is used to call the correct version from each base. |
| 8 | Constructor and Destructor Order | [`unit2/Program_08.cpp`](unit2/Program_08.cpp) | Shows that base class constructors run before derived class constructors, and destructors run in the reverse order. |
| 9 | Parameterized Base Constructor | [`unit2/Program_09.cpp`](unit2/Program_09.cpp) | A `Student` derived class passes a constructor argument up to the parameterized constructor of its `Person` base class. |
| 10 | Function Overriding | [`unit2/Program_10.cpp`](unit2/Program_10.cpp) | A virtual `move()` function in `Vehicle` is overridden differently by `Car` and `Boat` to demonstrate runtime polymorphism. |
| 11 | Abstract Class | [`unit2/Program_11.cpp`](unit2/Program_11.cpp) | An abstract `Shape` class declares a pure virtual `area()` function, implemented separately by `Rectangle` and `Circle`. |
| 12 | Virtual Base Class and Diamond Inheritance | [`unit2/Program_12.cpp`](unit2/Program_12.cpp) | `Student` and `Employee` both virtually inherit from `Person` so that `TeachingAssistant`, which inherits from both, has only one copy of `Person`. |
| 13 | Friend Class | [`unit2/Program_13.cpp`](unit2/Program_13.cpp) | The `Auditor` class is declared a friend of `Account`, allowing it to directly access the private `balance` member. |
| 14 | Nested Class | [`unit2/Program_14.cpp`](unit2/Program_14.cpp) | A `Department` class is defined inside a `University` class to show how nested classes are declared and used. |
| 15 | Mini-Project - Vehicle Rental System | [`unit2/Program_15.cpp`](unit2/Program_15.cpp) | A polymorphic rental billing system where `Car` and `Bike` derive from `Vehicle` and override rent calculation and display logic. |
| 16 | Mini-Project - Employee Payroll System | [`unit2/Program_16.cpp`](unit2/Program_16.cpp) | An abstract `Employee` class is extended by `PermanentEmployee` and `ContractEmployee`, each implementing its own salary calculation, demonstrated through a common `displayPaySlip()` function. |

## Unit III: Polymorphism

### List of Programs

| # | Title | Folder | Main Concept | Description |
|---|-------|--------|--------------|-------------|
| 1 | Function Overloading | [`unit3/Program_01.cpp`](unit3/Program_01.cpp) | Compile-time polymorphism | Three `add()` overloads demonstrate how the compiler statically resolves function calls based on parameter types and counts. |
| 2 | Area Calculator | [`unit3/Program_02.cpp`](unit3/Program_02.cpp) | Overloading with varied parameters | Three `calculateArea()` overloads compute areas for square, rectangle, and circle based on arguments provided. |
| 3 | Unary Minus Operator | [`unit3/Program_03.cpp`](unit3/Program_03.cpp) | Unary operator overloading | The `Number` class overloads unary `-` so that `-number` returns a new object with the negated value. |
| 4 | Prefix & Postfix Increment | [`unit3/Program_04.cpp`](unit3/Program_04.cpp) | Unary operator overloading | The `Counter` class implements both `++counter` (prefix) and `counter++` (postfix, distinguished by dummy `int`). |
| 5 | Complex Number Addition | [`unit3/Program_05.cpp`](unit3/Program_05.cpp) | Binary `+` operator overloading | Overloads binary `+` as a member function to add real and imaginary components of two complex numbers directly. |
| 6 | Distance Comparison | [`unit3/Program_06.cpp`](unit3/Program_06.cpp) | Relational operator overloading | The `Distance` class overloads `>` to enable natural relational comparison between two distance objects. |
| 7 | Non-Member / Friend Operator | [`unit3/Program_07.cpp`](unit3/Program_07.cpp) | Friend operator overloading | A friend `operator+(int, const Complex&)` allows algebraic expressions where the left-hand operand is a primitive type (`10 + c`). |
| 8 | Base Pointer Without Virtual Function | [`unit3/Program_08.cpp`](unit3/Program_08.cpp) | Static (early) binding | A `Base*` pointing to a `Derived` object calls `Base::display()`, illustrating compile-time static binding when functions lack `virtual`. |
| 9 | Base Pointer With Virtual Function | [`unit3/Program_09.cpp`](unit3/Program_09.cpp) | Runtime polymorphism | An `Animal*` pointer calls the overridden `sound()` method of the actual runtime object (`Dog`, `Cat`) via dynamic dispatch. |
| 10 | Base Reference With Virtual Function | [`unit3/Program_10.cpp`](unit3/Program_10.cpp) | Dynamic binding via references | Passing objects by `const Shape&` preserves the derived runtime type, invoking the correct `area()` without object slicing. |
| 11 | Abstract Class & Pure Virtual Function | [`unit3/Program_11.cpp`](unit3/Program_11.cpp) | Abstract interfaces | `Shape` defines `area()` as pure virtual (`= 0`), preventing instantiation and requiring derived classes (`Rectangle`) to implement it. |
| 12 | Collection of Shape Pointers | [`unit3/Program_12.cpp`](unit3/Program_12.cpp) | Polymorphic container processing | Uses `std::vector<std::unique_ptr<Shape>>` to store diverse shapes and invoke `displayName()` and `area()` dynamically in a loop. |
| 13 | Virtual Destructor | [`unit3/Program_13.cpp`](unit3/Program_13.cpp) | Safe dynamic deallocation | Demonstrates that declaring `virtual ~Base()` ensures `delete` through a base pointer properly calls derived and base destructors. |
| 14 | Object Slicing Demonstration | [`unit3/Program_14.cpp`](unit3/Program_14.cpp) | Object slicing vs. references | Demonstrates how passing by value slices away derived members and vtable, whereas passing by reference preserves full polymorphic behavior. |
| 15 | Payment System | [`unit3/Program_15.cpp`](unit3/Program_15.cpp) | Real-world polymorphic interface | An abstract `Payment` interface is implemented by `CardPayment`, `UpiPayment`, and `NetBankingPayment`, processed via a unified handler. |
| 16 | Employee Payroll Mini-Project | [`unit3/Program_16.cpp`](unit3/Program_16.cpp) | Integrated polymorphism project | An abstract `Employee` base class is extended by `PermanentEmployee` and `ContractEmployee`, each calculating salary polymorphically for pay slips. |