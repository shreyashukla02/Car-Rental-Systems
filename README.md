**Car Rental System**

This is a straightforward car rental system developed in C++. It enables users to manage customers, employees, and cars through a modular design, with separate classes for handling each aspect.

**Getting Started**

To begin, extract the code into a separate folder and compile it using a C++ compiler. After compilation, run the executable to start the system.

**Prerequisites**

A C++ compiler is required to build and run this system.

**Built With**

C++11

**Author**

Shreya Shukla

**Initial Database:**

- **CUSTOMERS:** ID, NAME, PASSWORD, DUES, RECORD, CURRENTLY RENTED CARS (number), OTHER DETAILS  
  Example:  
  1, C1, P1, 0, 40, 0, NA  
  2, C2, P2, 0, 40, 0, NA  
  3, C3, P3, 0, 40, 0, NA  
  4, C4, P4, 0, 40, 0, NA  
  5, C5, P5, 0, 40, 0, NA  

- **EMPLOYEES:** ID, NAME, PASSWORD, DUES, RECORD, CURRENTLY RENTED CARS (number), OTHER DETAILS  
  Example:  
  1, E1, P1, 0, 40, 0, NA  
  2, E2, P2, 0, 40, 0, NA  
  3, E3, P3, 0, 40, 0, NA  
  4, E4, P4, 0, 40, 0, NA  
  5, E5, P5, 0, 40, 0, NA  

- **CARS:** ID, CONDITION, OTHER DETAILS, AVAILABILITY, CURRENTLY RENTED BY (e.g., "E1" for employee with ID 1), BOOK DATE, DUE DATE  
  Example:  
  1, CAR1, NA, AVAILABLE, NA, NA, NA  
  2, CAR2, NA, AVAILABLE, NA, NA, NA  
  3, CAR3, NA, AVAILABLE, NA, NA, NA  
  4, CAR4, NA, AVAILABLE, NA, NA, NA  
  5, CAR5, NA, AVAILABLE, NA, NA, NA  

- **MANAGER ACCESS:** ID = 1, PASSWORD = manager  

**Assumptions:**

- Users are expected not to modify the provided text files.
- It is assumed that users will ensure that the corresponding car model is entered upon return.
- Most edge cases have been addressed, though some may be omitted due to time constraints.
- IDs for objects are assigned automatically using counters stored in "globals.txt". These are saved at the end of the main function, so please follow the program's exit instructions carefully to prevent data inconsistencies.

---
