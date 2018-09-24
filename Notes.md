# Java
Java is an object-oriented programming language and a platform developed by Sun Microsystems (eaten by Oracle). It uses the Write Once Use Anywhere Principle, meaning a compiled Java application can be run on any platform with a JVM. It's a flexible, popularlanguage; it allows devs to write large client-server web applications, desktop, and mobile apps,frameworks and libraries.

## Features
**Platform Independence**: The compiler converts source code to byte code. Then the JVM executes that bytecode.While each operating system has their own JVM implementation, every JVM can execute bytecode regardless of origin of said code.

**Clear, verbose syntax**: Java has C-like syntax, many syntax elements of the language are readble and widely used in programming. The Java API is also written using verbose, descriptive naming conventions making it simple to parse large code bases.

**Multi-paradigm**: While Java is Object-oriented, it supprts multiple paradigms including imperative, generic, concurrent, and functional.

**Garbage collection**: The JVM performs automatic memory deallocation of unused objects at runtime. Programs are written without the need for complex memory management. No need for destructors.

**Multithreading**: Java supports multithreading at both the language and standard library levels. It allows concurrent execution of several parts of a Java program.

**Object-Oriented Programming**: everything is represented as real world objects and communications between them. Although Java accomidates several paradigms, OOP is the foundation for most applications. In OOP the program is organized into object encapsulating related fields, representing its state, and methods usual to control that state or control related functions. When defining objects, Java reserves the keyword "class" which serves as their blueprint. In Java an object represents an instance of an object in memory of a class, and also every class implicitly inherits from the Object class, which provides useful convenience methods such as equals() and toString(). Java popularized several pillars of OOP design. Java focuses on four:

Encapsulation, Abstraction, Inheritance, and Polymorphism

*Abstraction* - by simplifying objects to a set of useful features, we hide irrelevant details, reduce complexity, and increase efficiency. Abstraction is important at all levels of software and computer engineering, but essential to designingt=useful objects. Complicated real-world objectsare reduced to simple representations.

*Encapsulation* - Objects should group related variables and functions and be in complete control over them. The state of an object should only change through the objects itself. (immutable objects are better) AKA data hiding, the object has sole responsibility for its own fields, and no outside object or function should interere.

*Inheritence* - Code reuse is an important principle of programming (DRY - Don't Repeat Yourself). New classes can reuse code from existing ones. This establishes a super/sub class relationship where the derived classes inherit fields and methods from its parents.

*Polymorphism* - Overloading/Overridng. With inheritance, an object can be referenced as an instance of its parent class. This provides flexibility when invoking inheritd methods with varying implementations in derived classes. Cat C = new Pet();
