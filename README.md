# Android-Interview-Question-2022-2023
Android interview questions for junior and seniors. 

## Java

### OOP Concept
- ### Class
  - Collection of objects is called class. It is a logical entity. A class can also be defined as a blueprint from which you can create an individual object. Class doesn't consume any space.
- ### Object
  - An object can be defined as an instance of a class, and there can be multiple instances of a class in a program.
- ### Method
  - A method is a collection of statements that perform some specific task, method can or can't return any result.
- ### Abstraction
  - Data abstraction is the process of hiding certain details and showing only essential information to the user. 
    - Abstract Classes
    - Interfaces
- ### Encapsulation
  - The meaning of Encapsulation, is to make sure that "sensitive" data is hidden from users.
    - declare class variables as private
    - provide public get and set methods to access and update the value of a private variable
- ### Inheritence
  - It is the mechanism in Java by which one class is allowed to inherit the features (fields and methods) of another class. 
    - Code Reusability
    - Method Overriding
    - Abstraction
  - ### Types of Inheritance
    1. Single Inheritance
       - In single inheritance, subclasses inherit the features of one superclass. In the image below, class Fruit serves as a base class for the derived class Mango.
    2. Multilevel Inheritance
       - Multilevel Inheritance, a derived class will be inheriting a base class, and as well as the derived class also acts as the base class for other classes. Class GrandFather serves as a base class for the derived class Father, which in turn serves as a base class for the derived class Son.
    3. Hierarchical Inheritance
       - One class serves as a superclass (base class) for more than one subclass. Class Wheel serves as a base class for the derived classes Cycle, Bike, and Car.
    4. Multiple Inheritance
       - One class can have more than one superclass and inherit features from all parent classes. Please note that ***Java does not support multiple inheritances*** with classes. In java, we can achieve multiple inheritances only through Interfaces. Class Car is derived from interfaces Wheel and Body.
    5. Hybrid Inheritance
       - It is a mix of two or more of the above types of inheritance. ***Since java doesn’t support multiple inheritances with classes, hybrid inheritance is also not possible with classes***. In java, we can achieve hybrid inheritance only through Interfaces.
- ### Polymorephism
  - When one object acquires all the properties and behaviors of a parent object, it is known as inheritance. It provides code reusability.
    - Overloading
    - Overriding 
