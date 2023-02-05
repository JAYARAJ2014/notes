# SOLID Principles

## Single Responsibility Principle - SRP

- Every software component should have only one responsibility.
- Every software component should have only one "reason to change". (More reasons to change will increase frequency of changes and probability of bugs)
- A component can be a module, class or method.
- Aim for higher cohesion between all methods of a class helps moving towards SRP

### Cohesion

- Degree to which various parts of a software components are related.

### Coupling

- Level of interdependency between components
- SRP => Higher Cohesion + Lose Coupling

## Open Close Principle

Open for extension / closed for modification

- New features getting added to the softeware component should not have to modify existing code.
- Should be extendable to add a new feature to add new behavior to it.
- OCP automatically follows SRP

## Liskov's Substitution Principle - LSP (From Barbara Liskov)

Objects should be replaceable with thier subtypes without affecting correctness of the program

- Move away from `is-a` way of thinking.
- Break the hierarchy
- Tell dont ask

## Interface Seggregation

No client should be forced to depend on methods it does not use.

## Dependancy Inversion

Highlevel modules should not depend on low-level modules. Both should depend on abstractions.
Abstractions should not depend on details. Details should depend on abstractions.

Closely related principles

- Inversion Of Control - IOC [Spring IOC Container / Unity in .NET/ Built-in to aspnet core / Inversify in Node]
- Dependency Injection
