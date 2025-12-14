
# Bank-Account: Encapsulation Demonstration

This Java program demonstrates the core concept of *encapsulation* in object-oriented programming (OOP).  
The BankAccount class enforces data protection by keeping all account information *private* and providing controlled access using dedicated *getter* and *setter* methods.  
The program ensures that invalid data, such as a negative balance, is not accepted.

---

## Key Principles of Encapsulation

The program achieves encapsulation by:

- *Data Protection*  
  Uses private data fields to protect account information.

- *Safe Reading*  
  Provides getter methods to safely read data.

- *Controlled Updates*  
  Uses setter methods with validation to update the balance.

- *Access Restriction*  
  Prevents direct access to account variables.

- *Design*  
  Demonstrates clean and simple object-oriented design.

---

## Program Demonstration Steps

The execution of the program highlights the benefits of encapsulation:

1. Three bank account objects are created.
2. Balances are updated using setter methods (deposits and withdrawals).
3. Negative balance updates or withdrawals exceeding the balance are rejected with an error message.
4. Account details are displayed using getter methods.
5. Direct access to private variables is not allowed, effectively proving encapsulation.

---
