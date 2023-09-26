# Restaurant_Management_System

This project on “Restaurant Management System” is a GUI application for managing day to day tasks and data of a small restaurant. The Restaurant Management System helps the restaurant manager to manage the restaurant more effectively and efficiently by computerizing meal ordering, billing, and managing employee details.The system utilizes file processing, for data retrieval and data manipulation. This system is designed to use by the manager/owner of a restaurant. It will help restaurant owners to keep track of their employee records like personal details, contact details, salary, etc. As well as, restaurant owner can manage order details, menu details, customer details and generate bills.

There are six classes in this system:
1. Employee class
2. Menu class
3. Dish class
4. Customer class
5. Order class
6. Final class
7. DbCon class

# Used cases of OOP concepts in the system

OOPs in java is to improve code readability and reusability by defining a Java program efficiently. The main principles of object-oriented programming are abstraction, inheritance, polymorphism, and encapsulation.

Abstraction

Abstraction is a process which displays only the information needed and hides the unnecessary information. We can say that the main purpose of abstraction is data hiding. Abstraction means selecting data from a large number of data to show the information needed, which helps in reducing programming complexity and efforts.There are also abstract class and abstract methods. An abstract class is a type of class that declares one or more abstract methods. An abstract method is a method that has a method definition but not implementation. Once we have modelled our object using data abstraction, the same sets of data can also be used in different applications—abstract classes, generic types of behaviors and object-oriented programming hierarchy. Abstract methods are used when two or more subclasses do the same task in different ways and through different implementations. An abstract class can have both the methods. In our program, Abstraction is achieved by declaring menu class as an abstract class and containing abstract methods.

Inheritance 

Inheritance is a method in which one object acquires/inherits another object’s properties, and inheritance also supports hierarchical classification. The idea behind this is that we can create new classes built on existing classes, when you inherit from an existing class, we can reuse methods and fields of the parent class. Inheritance represents the parent-child relationship. The subclass is a class which inherits properties of the superclass. This is also called a derived class. A superclass is a base class or parental class from which subclass inherits properties. There are five types of inheritance single, multilevel, multiple, hybrid and hierarchical. We use Single level inheritance by declaring Dish class inherits properties from menu class. Then menu class is parental class or base class, and dish class is child class or derived class.

Polymorphism 

Polymorphism refers to many forms, or it is a process that performs a single action in different ways. It occurs when we have many classes related to each other by inheritance. Polymorphism is of two different types, compile-time polymorphism and runtime polymorphism. Run time polymorphism is also called a dynamic method dispatch is a method in which a call to an overridden method is resolved at run time rather than compile time. In this method, the overridden method is always called through the reference variable. By using method overriding as required, we achieved runtime polymorphism. Runtime polymorphism in java is also known as Dynamic Binding which is used to call to an overridden methodthat is resolved dynamically at runtime rather than at compile-time. Generally, the concept of polymorphism is often expressed as one interface, multiple methods. This reduces complexity by allowing the same interface to be used as a general class of action.

Encapsulation 

Encapsulation is one of the concepts in OOPs concepts; it is the process that binds together the data and code into a single unit and keeps both from being safe from outside interference and misuse. In this process, the data is hidden from other classes and can be accessed only through the current class’s methods. Hence, it is also known as data hiding. Encapsulation acts as a protective wrapper that prevents the code and data from being accessed by outsiders. These are controlled through a well-defined interface.In our system, encapsulation is achieved by declaring the variables as private and providing public setter and getter methods to modify and view the variable values. In encapsulation, the fields of a class are made read-only or write-only. This method also improves the re-usability. Encapsulated code is also easy to test for unit testing.


![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/1.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/2.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/3.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/4.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/5.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/6.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/7.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/8.PNG)

![Screenshot 2022-11-01 162053](https://github.com/Cham99mahe/Restaurant_Management_System/blob/main/9.PNG)


