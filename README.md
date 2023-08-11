# Lecture 4
## Homework: 8/17/2023

### Exercise 1: Abstract Classes
**Task:** Create an abstract class named "Vehicle" with attributes `maxSpeed` and `fuelType`. Define a method `describeVehicle()` that each subclass must implement. Create subclasses "Car" and "Boat" that extend "Vehicle" and implement the `describeVehicle()` method.
**Explanation:** This exercise will introduce the concept of abstract classes and their significance in OOP. You'll learn how to use the `abstract` keyword and understand how it enforces certain behaviors in subclasses.

### Exercise 2: Interfaces
**Task:** Create an interface "Drivable" with methods `start()`, `drive()`, and `stop()`. Make the "Car" class from the previous exercise implement this interface and provide implementations for all the methods.
**Explanation:** With this task, you'll delve into the concept of interfaces in OOP. You'll explore how interfaces can be used to define a contract that classes can adhere to.

### Exercise 3: Polymorphism
**Task:** Create a method `displayVehicleInfo(Vehicle vehicle)` that takes a "Vehicle" object as a parameter and invokes the `describeVehicle()` method on it. In your main method, pass instances of both "Car" and "Boat" to this function.
**Explanation:** This exercise demonstrates the power of polymorphism. You'll witness how you can use a reference of a parent class (or interface) to refer to any of its child objects.

### Exercise 4: Composition
**Task:** Introduce a "Engine" class with attributes `horsePower` and `type`. Modify the "Car" class to contain an instance of the "Engine" class. This relation should demonstrate that a "Car" has an "Engine".
**Explanation:** Composition is a design principle in OOP where classes are composed using references to other classes. Through this exercise, you'll understand how to use composition to represent the "has-a" relationship.

### Exercise 5: Method Overriding
**Task:** Override the `toString()` method in the "Car" and "Boat" classes to return a string representation of the respective objects, displaying their attributes.
**Explanation:** Method overriding is a feature that allows a subclass to provide a specific implementation of a method that's already defined in its superclass. You'll practice overriding to modify the behavior of a method in the child class.

### Exercise 6: Advanced Geometric Shapes using Interfaces
**Task:** Build upon the geometric shapes example. Create an interface "Drawable" with methods `draw()` and `resize()`. Make your shape classes (like "Square", "Circle") implement this interface. Additionally, add a method `rotate()` in another interface "Rotatable" and implement it in suitable shape classes.
**Explanation:** This exercise further builds on your geometric shapes understanding by integrating interface-driven design. You'll recognize how interfaces can be used to impart additional behaviors to classes, ensuring flexibility and scalability in the design.

These tasks for Lecture #4 will guide students through advanced OOP concepts, allowing them to expand their understanding and apply these principles to a variety of situations. This homework will challenge them to think critically about their designs and consider the best practices and principles discussed during the lecture.