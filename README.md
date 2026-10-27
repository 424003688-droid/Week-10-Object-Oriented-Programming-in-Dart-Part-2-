# Week 10: Enhanced OOP Console Application

This repository contains my submission for the PC16 Mobile Development Week 10 Individual Task. It is a Dart console application that demonstrates advanced Object-Oriented Programming principles.

## Rubric Requirements Fulfilled

* **Inheritance (25 pts):** Uses Student as a base class, which is extended by two derived classes: UndergraduateStudent and GraduateStudent.
* **Polymorphism (25 pts):** Both derived classes override the printRecord() and evaluatePerformance() methods to provide specific, distinct behaviors for graduates and undergraduates.
* **Abstract Class / Interface (25 pts):** Includes an Evaluatable abstract class that defines a contract (evaluatePerformance()) which the classes must implement.
* **Mixin (25 pts):** Implements an Extracurriculars mixin outside the main inheritance chain, which is shared with the UndergraduateStudent class using the with` keyword to track club activities.

## How to Run
To run this application, ensure you have the Dart SDK installed, and execute the following command in your terminal:

bash
dart run week10_oop_task.dart
