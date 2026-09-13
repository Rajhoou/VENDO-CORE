
This design is optimized with SOLID PRINCIPLE>
SOLID is a set of five design principles that make object-oriented code easier
to maintain, extend, and test. Single Responsibility -a class should have only one reason to change.Open/Closed means code should be open 
for  extension but closed for modification - add new behaviors via new classes, not by editing existing ones. The Liskov Substitution Principle means a subclass  
should be usable anywhere its parent class is expected, without breaking behavior. Interface Segregation means interfaces should be small and specific, so classes 
aren't forced to implement methods that they don't need. Dependency Inversion means high-level logic should depend on abstractions, not concrete Implementations- dependencies get injected rather than 
hardcoded. In VendoCore, these principles turn a single, tangled  'VendingMachine class into independent,
swappable components: 'paymentmethod, 'TransactionLog,' and 'Inventory'.
  
