# JAVASCRIPT CLASS

### Class
Class is blueprint for creating object , providing intial value 
for member variable or attribute and implementation of behavior ( function or method).
In javascript , class is in fact a " special function " . The important
difference is function is hoisted but class declaration is not hoisted (throw error)

Example of a class : 
```bash
class Animal {
   constructor(name) {
       this.name =name
   }
let dog = new Animal("bailey")
console.log(dog.name)

```
Javascript object system is based on prototypes , not classes.
In JavaScript, class inheritance is implemented on top of prototypal inheritance, but that does not mean that it does the same thing :
JavaScript’s class inheritance uses the prototype chain to wire the child `constructor.prototype` to the parent `constructor.prototype` for delegation. Usually, the `super()` constructor is also called. Those steps form single-ancestor parent/child hierarchies and create the tightest coupling available in OO design.
.Prototypal Inheritance means a prototype is a working object instance. Objects inherit directly from other objects.



### Object
Object is a collection of property that have key and value. And a property value can be 
function or known as method.
There are 4 ways to create an Object : 

- Object literal
- Function declaration
- Constructor Function ( keyword new)
- Object.create
