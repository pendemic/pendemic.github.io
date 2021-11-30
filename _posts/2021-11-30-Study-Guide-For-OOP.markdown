
<html>
<head>
    <meta charset="utf-8" />
    <title>Study Guide for OOP</title>
</head>
<body>
Four Pillars of Object Oriented Programming

Basic Terminologies

**Object** - Instance of a class/ working entity of a class. Objects don&#39;t need to be created if the class has static methods.

**Class** - This is the model or standard about the capability of what an object can do. Classes do not consume memory.

**Method** - Can modify a class state that would apply across all the instances of a class

**Instance** - These are like Objects. A blueprint for a car design is the class description, all the cars manufactured from that blueprint are objects of that class. Your car that has been made from that blueprint is an instance of that class.

**Constructor** - Is a special method whose name is the same as the class name. Serve to initialize objects.

**Interface** - A special type of class that contains methods but not their definitions. You cannot create objects, you need to implement that interface and define methods for implementation.

**Abstract Class** - special class containing abstract methods. The abstract methods inside are not implemented, only declared. So when a subclass inherits the class they need to define and implement them.

**Difference** - The main difference between the two is that, when an interface is implemented, the subclass must define all its methods and provide its implementation. Whereas when an abstract class is inherited, the subclass does not need to provide the definition of its abstract method, until and unless the subclass is using it

**Access Modifiers** - Special keywords that control the accessibility of entities like classes and methods. Examples - Public, Private. Play a vital role in achieving encapsulation.

Four Principles of OOP:

**Encapsulation**

Encapsulation is when each object inside of a class maintains a private state. Other objects can not access this state directly, instead they can only invoke a list of public functions. In order to communicate with the object, you will need to utilize the methods provided. To bind things. Example: A vending machine. You request a bag of chips from the machine and it gives you chips. The vending machine is a class and contains methods for its mechanisms and operations. They are all encapsulated in the vending machine.

Data Hiding - Hides unwanted information, such as restricting access to any member of an obj

Data Binding - binding the data members and the methods together as a whole, as a class

**Abstraction**

Abstraction is an extension of encapsulation. It is the process of selecting data from a larger pool to show only the relevant details to the object. An advantage to abstraction is being able to apply the same information to other applications with little or no modification. Example: Driving a car. You do not need to know the details on how the engine works or how your transmission works to drive the vehicle. You only need to know functions like how to steer or how to put the car in drive. This is abstraction because you are choosing only the relevant details that you need to operate the vehicle. Also being able to apply these details to other vehicles and being able to operate them with little to no modification.

**Inheritance**

Inheritance is the ability to acquire some/all properties of another object. Example: An Apple can inherit properties from a fruit class such as having seeds. But then the apple sub class would contain details such as being red, round and having a stem.

Sub class - An entity which inherits from another class, child class

Superclass - An entity which allows subclasses or child classes to inherit from itself.

**Polymorphism**

Polymorphism gives us a way to use a class exactly like its parent so there is no confusion with mixing types. Each child sub class keeps its own functions/methods as they are. To use something in different forms. Example: We use milk for drinking but it can also be used for other things like making curd or butter. Example(2):Function overloading - In which you use the same name but the operations are different.

Why use OOP:

- Helps users to understand the software easily, although they don&#39;t know the actual implementation.
- The readability, understandability and maintainability of the code increase multifold
- Big software can be easily written and managed easily using OOPs.
- Helpful in solving complex problems
- Promotes code reuse, reducing redundancy
</body>
</html>