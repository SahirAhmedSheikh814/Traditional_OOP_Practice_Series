# 📌 Python OOP Challenges ✅  

This repository contains solutions to 21 Python programming challenges focused on Object-Oriented Programming (OOP) concepts. Each challenge demonstrates a specific OOP feature or technique, such as classes, inheritance, decorators, and exception handling.

---

### **Table of Contents** 
- Project Overview
- Challenges
- License

## Project Overview

This project showcases Python implementations of various OOP concepts through well-documented and modular code. Each challenge is implemented as a standalone Python script, making it easy to understand and test individual concepts. The solutions are designed to be clear, concise, and aligned with Python best practices.

## Challenges

The following challenges are included in this repository:

1. **Using self**: A Student class with name and marks attributes, initialized using self in a constructor, and a display() method to print details.
2. **Using cls**: A Counter class that tracks the number of objects created using a class variable and a class method with cls.
3. **Public Variables and Methods**: A Car class with a public brand variable and a start() method, accessible from outside the class.
4. **Class Variables and Class Methods**: A Bank class with a class variable bank_name and a class method to change it, affecting all instances.
5. **Static Variables and Static Methods**: A MathUtils class with a static method add(a, b) to compute the sum of two numbers.
6. **Constructors and Destructors**: A Logger class that prints messages during object creation and destruction.
7. **Access Modifiers**: Public, Private, and Protected: An Employee class with name (public), _salary (protected), and __ssn (private) variables, demonstrating access behavior.
8. **The super() Function**: A Teacher class inheriting from Person, using super() to initialize the base class constructor and adding a subject field.
9. **Abstract Classes and Methods**: An abstract Shape class with an abstract area() method, implemented by a Rectangle subclass.
10. **Instance Methods**: A Dog class with name and breed variables and a bark() instance method.
11. **Class Methods**: A Book class with a class variable total_books and a class method to increment it.
12. **Static Methods**: A TemperatureConverter class with a static method celsius_to_fahrenheit(c) to convert temperatures.
13. **Composition**: A Car class that uses composition by including an Engine object and accessing its methods.
14. **Aggregation**: A Department class that aggregates an independently created Employee object.
15. **Method Resolution Order (MRO) and Diamond Inheritance**: Classes A, B, C, and D demonstrating MRO in a diamond inheritance structure.
16. **Function Decorators**: A log_function_call decorator that logs function execution, applied to a say_hello() function.
17. **Class Decorators**: A class decorator add_greeting that adds a greet() method to a Person class.
18. **Property Decorators**: @property, @setter, and @deleter: A Product class with a _price attribute managed by property decorators.
19. **callable() and call()**: A Multiplier class with a __call__() method to multiply inputs by a factor, tested with callable().
20. **Creating a Custom Exception**: A custom InvalidAgeError exception raised by a check_age(age) function for ages below 18.
21. **Make a Custom Class Iterable**: A Countdown class that iterates from a start number down to 0 using __iter__() and __next__().

## License

This project is licensed under the MIT License. See the LICENSE file for details.
