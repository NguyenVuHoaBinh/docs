
_SOLID design principles are a set of guidelines that help developers create better-structured, more manageable code_
![[Pasted image 20250505165536.png]]

I. S - Single Responsibility Principle (SRP)
- A class should have one reason to change.
- A class should only do one thing or be responsible for one task.
- -> If something needs to change,, it will only affect that class.

II. O - Open/Closed Principle (OCP)
- Software entities(class, method) should be open for extension but closed for modification.
- -> To avoid making unnecessary changes to existing code, which can introduce new bugs.

III.  L - Liskov Substitution Principle (LSP)
- Objects of a sub-class should be able to replace objects of the super-class without affecting the correctness of the program.
- -> Sub-class should not break the functionality defined in the parent class, ensuring consistent behavior across the system.

IV. I - Interface Segregation Principle (ISP)
- Clients should not be forced to depend on interfaces they do not use.
- Instead of having one large interface, break it own into smaller, more specific ones.
- -> Each class implements only the methods it needs, make the code cleaner and easier to work with.

V. D - Dependency Inversion Principle (DIP)
- High-level modules should not depend on low-level modules.
- Both should depend on abstractions.
- -> Reduce tight coupling between modules, make the system more flexible and easier to modify.