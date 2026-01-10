* * *

# Object-Oriented Programming (OOP) Projects

This section focuses on OOP concepts in Python, including classes, inheritance, methods, and dunder (special) methods. Learners will see how OOP helps organize code, reuse logic, and build scalable programs, which is essential for AI/ML applications.

* * *

## Project 1: Student Management System

Concepts Used:

-   Classes
    
-   Methods
    
-   Attributes
    

Project Idea:  
Create a Student Management System where each student is represented as an object with attributes like name, age, grades, and methods to calculate GPA or display details.

How Concepts Are Applied:

1.  Classes & Attributes: Define a Student class with name, age, and grades attributes.
    
2.  Methods: Create methods like calculate\_gpa() and display\_info().
    
3.  Objects: Instantiate multiple students and manage them in a list.
    

Outcome:  
Learners understand how to structure real-world entities as objects, encapsulate behavior, and make code modular.

* * *

## Project 2: Inheritance in Vehicles

Concepts Used:

-   Inheritance
    
-   Methods Overriding
    

Project Idea:  
Build a Vehicle Management System:

-   Base class Vehicle with attributes brand, year, speed
    
-   Child classes Car and Bike that inherit from Vehicle and have additional attributes/methods
    

How Concepts Are Applied:

1.  Inheritance: Child classes reuse properties and methods of the base Vehicle class.
    
2.  Method Overriding: Child classes override methods like display\_info() to show extra details.
    

Outcome:  
Learners see code reuse and hierarchical relationships, which is essential for designing scalable AI/ML projects (e.g., different types of models or data structures).

* * *

## Project 3: Bank Account Simulation

Concepts Used:

-   Classes & Methods
    
-   Dunder Methods (\_\_str\_\_, \_\_repr\_\_, \_\_eq\_\_)
    

Project Idea:  
Simulate a bank account system where each account has:

-   Account holder’s name, balance
    
-   Methods for deposit, withdraw, transfer
    
-   Special behavior using dunder methods
    

How Concepts Are Applied:

1.  Dunder Methods:
    

-   \_\_str\_\_ to print account details
    
-   \_\_eq\_\_ to compare two accounts by balance
    

3.  Encapsulation: Use private attributes like \_\_balance with getter/setter methods.
    
4.  Methods: Deposit, withdraw, and transfer operations encapsulated inside the class.
    

Outcome:  
Learners understand special methods and encapsulation, making Python objects more robust and reusable.

* * *

## Project 4: Library Management System (Advanced)

Concepts Used:

-   Classes & Methods
    
-   Inheritance
    
-   Polymorphism
    
-   Dunder Methods
    

Project Idea:  
Create a Library Management System with:

-   Base class Book
    
-   Derived classes EBook and PrintedBook with overridden methods for display or borrowing rules
    
-   Dunder methods to print summaries or compare books
    

How Concepts Are Applied:

1.  Inheritance & Polymorphism: Derived classes reuse base class attributes and override methods for different behaviors.
    
2.  Dunder Methods: Use \_\_str\_\_ and \_\_repr\_\_ to display book info cleanly.
    
3.  Methods & Objects: Add, borrow, return books; track borrowers using objects.
    

Outcome:  
Learners experience real-world OOP applications, combining multiple OOP concepts into a single interactive project.

* * *

## Learning Impact

By completing these projects, learners will:

-   Understand classes, objects, and methods
    
-   Apply inheritance and method overriding for code reuse
    
-   Use dunder methods to enhance object behavior
    
-   Build scalable, modular programs, preparing them for AI/ML projects where models, datasets, or pipelines can be represented as objects
    

* * *

  

* * *

# OOP Project: Abstraction

* * *

## Shape Area Calculator

Concepts Used:

-   Abstract Base Class (ABC)
    
-   Inheritance
    
-   Method Overriding
    

Project Idea:  
Create a program to calculate the area of different shapes (e.g., Circle, Rectangle, Triangle).

How Concepts Are Applied:

1.  Abstract Base Class:
    

-   Create a class Shape with an abstract method area() using from abc import ABC, abstractmethod.
    

3.  Inheritance:
    

-   Subclasses Circle, Rectangle, Triangle inherit from Shape.
    

5.  Method Overriding:
    

-   Each subclass implements its own version of area().
    

Outcome:  
Learners understand abstraction and force implementation of methods in subclasses, a critical concept in designing scalable AI/ML pipelines or frameworks.

* * *

  

Employee Management System (Abstract Methods)

Concepts Used:

-   Abstract Base Class
    
-   Inheritance
    
-   Method Overriding
    
-   Polymorphism
    

Project Idea:  
Create a system to manage different types of employees: FullTimeEmployee and PartTimeEmployee.

How Concepts Are Applied:

1.  Abstract Base Class:
    

-   Employee class with abstract method calculate\_salary().
    

3.  Inheritance:
    

-   Subclasses FullTimeEmployee and PartTimeEmployee inherit from Employee.
    

5.  Method Overriding:
    

-   Each subclass implements its own salary calculation.
    

7.  Polymorphism:
    

-   Store all employees in a list and call calculate\_salary() on each object without worrying about the type.
    

Outcome:  
Learners practice abstraction and polymorphism together, preparing them for complex AI/ML systems where multiple components follow a common interface.

* * *

### Learning Impact

By adding these projects, learners will now have full coverage of OOP:

-   Classes, objects, attributes, methods ✅
    
-   Inheritance, polymorphism ✅
    
-   Dunder methods ✅
    
-   Encapsulation ✅
    
-   Abstraction ✅