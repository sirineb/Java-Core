# Java-Core Cheat sheet
## Java Compilation/Runtime Notions
### Java compiler
Checks syntax rules, then writes bytecode in .class files. It differs from other language compilers, which write instructions for the CPU.
### The JVM
At runtime, the JVM interprets .class files and executes its instructions on the native hardware platform for which the JVM was written (Linux, Windows and mobile). The JVM interprets the bytecode just as a CPU would interpret assembly. The difference is that the JVM is a software.
### The garbage collector
Java keeps up with memory allocation for you. When a Java application creates an object instance at runtime, the JVM automatically allocates memory space for that object. The Java garbage collector runs in the background, keeping track of which objects the application no longer needs and reclaiming memory from them. 
### The Java Development Kit
The JDK includes the compiler and a complete class library of prebuilt utilities.
### The Java Runtime Environment
The JRE includes the JVM, code libraries, and components that are necessary for running programs that are written in the Java language.
## Java Language/Structure Notions
### What is an object?
An object is an entity that contains attributes and behavior. 
### Encapsulation
Using modifiers, it’s possible to vary the nature of object relationships from public to private.
### Inheritance
In structured programming, it's common to copy a structure and add or modify the attributes which generates duplicated code. OOP introduces inheritance, to "copy" the attributes and behavior of the source classes. If some of those attributes or behaviors need to change, you override them.
### Polymorphism
Objects belonging to the same branch of a hierarchy, when told to do the same thing, can manifest that behavior differently.	
### Static and instance methods
There are two types of methods: instance and static. Static methods or class methods’ don't dependent on object's state. Object instance are not needed to invoke them. Just the name of the class.
### Access Specifier
* public: Any object in any package can see the variable. 	
* protected: Any object defined in the same package, or a subclass (in any package), can see the variable.
* No specifier: Only objects whose classes are defined in the same package can see the variable.
* private: 	Only the class containing the variable can see it. 
