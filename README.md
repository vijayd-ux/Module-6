# *🐍 Python OOP: Polymorphism with Classes*

_AIM:_
To create two specific classes — Beans and Mango. Then, create a generic function that can accept any object and determine its type (Fruit or Vegetable) and color, using polymorphism.

_ALGORITHM:_

Create Class Beans:
->Define type() method that prints "Vegetable".
->Define color() method that prints "Green".
Create Class Mango:
->Define type() method that prints "Fruit".
->Define color() method that prints "Yellow".
Define Generic Function func(obj):
->Call obj.type() and obj.color() — this works with both Beans and Mango objects, showcasing polymorphism.
Create Objects:
->Instantiate Beans and Mango.
->Pass them to func() and execute the program.

_PROGRAM:_

<img width="329" height="414" alt="image" src="https://github.com/user-attachments/assets/4351674d-a1d6-4175-b375-331d3325189d" />

_OUTPUT:_

<img width="425" height="242" alt="image" src="https://github.com/user-attachments/assets/ad02a917-70b6-4bde-9c1b-272120997165" />

_RESULT:_
Thus , the program has been executed succesfully.

# *🐍 Python OOP: Operator Overloading (Less Than <)*

_AIM:_
To write a Python program that demonstrates operator overloading by overloading the less than (<) operator using a custom class.

_ALGORITHM:_

Create Class A:
->Define the __init__() method to initialize the object with a value a.
Overload the < Operator:
->Define the __lt__() method with logic:
    =>If self.a < o.a, return "ob1 is less than ob2"
    =>Else, return "ob2 is less than ob1"
Create Objects:
->Instantiate two objects ob1 and ob2 with values.
Use < Operator:
->Use print(ob1 < ob2) to trigger the overloaded behavior.

_PROGRAM:_

<img width="451" height="268" alt="image" src="https://github.com/user-attachments/assets/14309353-7bf3-475f-bf7e-7d64f2660092" />

_OUTPUT:_

<img width="590" height="183" alt="image" src="https://github.com/user-attachments/assets/bbd35f49-34dd-4d18-bc2d-f85743c26611" />

_RESULT:_
Thus , the program has been executed succesfully.

# *🐍 Python OOP: Abstract Class & Method Example*

_AIM:_
To create an abstract class named Shape with an abstract method calculate_area, and implement this method in two subclasses: Rectangle and Circle.

_ALGORITHM:_

Import ABC module:
->Use from abc import ABC, abstractmethod to define abstract classes and methods.
Create Abstract Class Shape:
->Define an abstract method calculate_area() with @abstractmethod.
Create Subclass Rectangle:
->Set default values for length and breadth.
->Override calculate_area() to compute the rectangle area.
Create Subclass Circle:
->Set default value for radius.
->Override calculate_area() to compute the circle area.
Create Objects & Call Methods:
->Instantiate Rectangle and Circle.
->Call their calculate_area() methods.

_PROGRAM:_

<img width="564" height="604" alt="image" src="https://github.com/user-attachments/assets/d5c58f65-f37c-403f-b4a5-c7e78273ae59" />

_OUTPUT:_

<img width="808" height="218" alt="image" src="https://github.com/user-attachments/assets/80f43e30-733f-4a5c-a911-771ae781467a" />

_RESULT:_
Thus , the program has been executed succesfully.

# *🐍 Python OOP: Encapsulation with Private Members*

_AIM:_
To implement Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth.

_ALGORITHM:_

Define the Class:
->Create a class Rectangle with two private attributes: __length and __breadth.
Initialize Variables:
->Use the __init__() constructor to set initial values for __length and __breadth.
Print Values:
->Display the private variables from within the class to demonstrate access.
Instantiate the Object:
->Create an object of the Rectangle class to trigger the constructor.

_PROGRAM:_

<img width="578" height="390" alt="image" src="https://github.com/user-attachments/assets/fffbe11a-110b-4b1a-9566-16e3a95cd569" />

_OUTPUT:_

<img width="476" height="221" alt="image" src="https://github.com/user-attachments/assets/4253e986-a9ce-4460-bc06-4a63bdbb7487" />

_RESULT:_
Thus , the program has been executed succesfully.

# *🐟 Method Overriding-Fish and Shark Class Inheritance in Python*

_AIM:_
To write a Python program that demonstrates class inheritance by creating a parent class Fish with a method type, and a child class Shark that overrides the type method.

_ALGORITHM:_

Define the Fish class with a method named type() that prints "fish".
Define the Shark class as a subclass of Fish, and override the type() method to print "shark".
Create an instance of the Fish class named obj_goldfish.
Create an instance of the Shark class named obj_hammerhead.
Use a for loop to iterate over both objects.
Within the loop, call the type() method using the loop variable.
Output will demonstrate method overriding: printing "fish" and "shark" accordingly.

_PROGRAM:_

<img width="428" height="282" alt="image" src="https://github.com/user-attachments/assets/4ffbd5f5-bf97-4ad6-8f23-bf1f9fda63fd" />

_OUTPUT:_

<img width="395" height="220" alt="image" src="https://github.com/user-attachments/assets/a0361373-b893-4d14-b097-ca152c0716b3" />

_RESULT:_
Thus , the program has been executed succesfully.

