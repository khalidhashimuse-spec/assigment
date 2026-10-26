Superclass: Employee. Subclasses: FullTimeEmployee, PartTimeEmployee,  and Manager.

Inheritance reduces code duplication because subclasses reuse the variables and methods of the Employee class instead of writing the same code again.

The calculateSalary() method demonstrates polymorphism because each subclass provides its own implementation of the method.

@Override indicates that a subclass is overriding a method from its parent class. It also helps the compiler detect mistakes in the method declaration.




MedicalService is declared abstract because it provides a common structure for different medical services and contains an abstract method that subclasses must implement.

No, an object cannot be created directly from MedicalService because it is an abstract class. Objects must be created from its concrete subclasses.

An abstract method has no method body and must be implemented by a concrete subclass. A concrete method has a method body and contains executable code.

Each concrete subclass must implement calculateTotalCost() because every medical service has its own way of calculating the total cost.
