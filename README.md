# Design Patterns Repository

Welcome to the Design Patterns Repository, a playground for exploring software design concepts through TypeScript implementations. Dive into the world of design patterns categorized into three main types: Behavioral, Creational, and Structural. Each pattern offers a unique perspective on solving common software design challenges.

## 🧠 Behavioral Patterns
Behavioral patterns focus on how objects interact and communicate with each other. They help in defining the responsibilities of objects and the algorithms for their collaboration.

### Examples of Behavioral Patterns:
- **Observer Pattern**: Defines a one-to-many dependency between objects, so that when one object changes state, all its dependents are notified and updated automatically.
- **Strategy Pattern**: Defines a family of algorithms, encapsulates each algorithm, and makes them interchangeable. It lets the algorithm vary independently from clients that use it.
- **Command Pattern**: Encapsulates a request as an object, thereby allowing for parameterization of clients with different requests, queuing of requests, and logging of requests.
- **State Pattern**: Allows an object to alter its behavior when its internal state changes. The object will appear to change its class.

## 🏗️ Creational Patterns
Creational patterns deal with object creation mechanisms, trying to create objects in a manner suitable to the situation. They provide flexibility in creating new instances of objects.

### Examples of Creational Patterns:
- **Factory Method Pattern**: Defines an interface for creating objects, but lets subclasses alter the type of objects that will be created.
- **Singleton Pattern**: Ensures a class has only one instance and provides a global point of access to that instance.
- **Abstract Factory Pattern**: Provides an interface for creating families of related or dependent objects without specifying their concrete classes.
- **Builder Pattern**: Constructs a complex object step by step. It separates the construction of a complex object from its representation, allowing the same construction process to create various representations.

## 🛠️ Structural Patterns
Structural patterns deal with object composition, creating relationships between objects to form larger structures. They help in simplifying the design by identifying simple ways to realize relationships between entities.

### Examples of Structural Patterns:
- **Adapter Pattern**: Allows incompatible interfaces to work together by creating a bridge between them.
- **Decorator Pattern**: Allows behavior to be added to individual objects, either statically or dynamically, without affecting the behavior of other objects from the same class.
- **Composite Pattern**: Composes objects into tree structures to represent part-whole hierarchies. It lets clients treat individual objects and compositions of objects uniformly.
- **Facade Pattern**: Provides a unified interface to a set of interfaces in a subsystem. It defines a higher-level interface that makes the subsystem easier to use.

## Getting Started

1. Explore the folders in each category to discover individual design patterns.
2. Each pattern folder contains an `index.ts` file with the TypeScript implementation and an `output.md` file documenting the output.
3. Dive into the explanations and implementations to understand how each pattern works.

Let's design the future, one pattern at a time!