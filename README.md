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


## Architecture Pattern

### MVC(Model View Controller) https://bit.ly/geeksforgeeks-mvc
  - The MVC pattern suggests splitting the code into 3 components. While creating the class/file of the application, the developer must categorize it into one of the following three layers:
  
  ![](https://media.geeksforgeeks.org/wp-content/uploads/20201002214740/MVCSchema.png)
  - ### Model
    - This component stores the application data. It has no knowledge about the interface. The model is responsible for handling the domain logic(real-world business rules) and communication with the database and network layers.
  - ### View
    - It is the UI(User Interface) layer that holds components that are visible on the screen. Moreover, it provides the visualization of the data stored in the Model and offers interaction to the user.
  - ### Controller
    - This component establishes the relationship between the View and the Model. It contains the core application logic and gets informed of the user’s behavior and updates the Model as per the need.
### MVP(Model View Presenter) https://bit.ly/geeksforgeeks-mvp
  - MVP pattern overcomes these challenges of MVC and provides an easy way to structure the project codes. The reason why MVP is widely accepted is that it provides modularity, testability, and a more clean and maintainable codebase. It is composed of the following three components:
  
  ![](https://media.geeksforgeeks.org/wp-content/uploads/20201024233154/MVPSchema.png)
  - ### Model
    - Layer for storing data. It is responsible for handling the domain logic(real-world business rules) and communication with the database and network layers.
  - ### View
    - UI(User Interface) layer. It provides the visualization of the data and keep a track of the user’s action in order to notify the Presenter.
  - ### Presenter
    -  Fetch the data from the model and applies the UI logic to decide what to display. It manages the state of the View and takes actions according to the user’s input notification from the View.
### MVVM(Model View ViewModel) https://bit.ly/geeksforgeeks-mvvm
  - MVVM pattern is the industry-recognized software architecture pattern that overcomes all drawbacks of MVP and MVC design patterns. MVVM suggests separating the data presentation logic(Views or UI) from the core business logic part of the application. 
  
  ![](https://media.geeksforgeeks.org/wp-content/uploads/20201002215007/MVVMSchema.png)
  - ### Model
    - This layer is responsible for the abstraction of the data sources. Model and ViewModel work together to get and save the data.
  - ### View
    - The purpose of this layer is to inform the ViewModel about the user’s action. This layer observes the ViewModel and does not contain any kind of application logic.
  - ### ViewModel
    - It exposes those data streams which are relevant to the View. Moreover, it serves as a link between the Model and the View.


## Agile Methodology https://bit.ly/5280software-agile-methodology
  - The Agile model is a project management methodology purposely adopted for the development of sophisticated software. The framework allows for iterations, which helps a lot in minimizing mistakes and errors that commonly occur. 
  - The model divides the project into a series of development cycles or short time boxes, which are assigned to each professional on the project team. It is a collaborative approach the allows a response to rapid change.  It is flexible enough to accommodate changes in project requirements throughout the mobile app development lifecycle.   
  - ## Scrum 
    - Focuses on the management aspects of software development in intricate knowledge work, research and advanced technologies with an emphasis on teamwork, iteration and accountability.
