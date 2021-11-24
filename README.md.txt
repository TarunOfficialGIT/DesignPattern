# Structural Design Patterns
## Table of Contents
- [Adapter](#adapter)
- [Composite](#composite)
- [Decortor](#decorator)
- [Facade](#facade)

## Adapter <a name="adapter"></a>
- Bridge between 2 interfaces (Useful when we work with Legacy code)

### Disadvantages
- No new functionalities
- Multiple Adapters

## Composite <a name="composite"></a>
- Tree structure
- Component
- Leaf
- Composite

### Disadvantages
- Very costly to create more composite impl
- Overly simple

## Decorator <a name="decorator"></a>
- Wrapper
- Add functionality or behavior
- Single Responsibility Principle
- Dynamically compose behavior
- Inheritance and Composition

## Disadvantages
- New Class for every feature
- no of objects (more)
- more comples for the clients

## Facade <a name="facade"></a>
- Make API easy 
- Interface not required
- usually a refactoring pattern

## Disadvantages
- Over usage
- Clean up design pattern


# Creational Design Patterns
## Table of Contents
- [Singleton](#singleton)
- [Builder](#builder)
- [Factory](#factory)
- [AbstractFactory](#absfactory)

## Singleton <a name="singleton"></a>
- Static in nature
- Thread safe
- Private Constructor
- Private Instance of the Class
- No parameters to the Constructor

### Disadvantages
- Overusage
- Unit testing
- Slow down
- Confused with factory design pattern (with arguments)

## Builder <a name="builder"></a>
- Solves the multiple constructor problem (telescoping constructors)
- static inner class (builder class)
- internally required constructor
- removes the need for setters

### Disadvantages
- Immutable
- inner static class
- Designed first
- Complex

## Factory <a name="factory"></a>
- Doesn't expose instantiation or the creation logic
- Subclasses create the objects
- Common Abstract/Interface
- Framework, the client/ the implementation uses the factories

### Disadvantages
- Complex
- Creation in Subclasses
- Refactoring

## Abstract Factory <a name="absfactory"></a>
- Factory of factories/ related object / colelctions of factories
- Common Abstract/Interface
- Subclasses create the objects

### Disadvantages
- The code is complex
- Refactoring factory
- More control to client