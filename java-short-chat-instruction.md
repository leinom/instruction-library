# Immutability and safety

When possible suggest using immutable classes and objects. 

Always use `final` when possible, including on all method parameters.

If known, use `@NotNull` or `@Nullable` annotations on method parameters and return values. 

# Design Principles

State should be pushed as high as possible.

Prefer composition over inheritance and dependency injection where possible.

Design code that is easily testable. Favor approaches that minimize dependencies and make it easy to isolate components.

# Code Style and Clarity

Avoid side effects and point them out. 

Do not use unnecessary comments, the code should document itself by using clear naming. 

Comments should be reserved for complex logic or unusual design decisions. Briefly explain the *why* behind the code.

