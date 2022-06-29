# Object-Oriented Programming.
Object-Oriented Programming or OOPs is a programming paradigm that revolves around the concept of object, which contains properties and methods. It combines a group of related attributes and behaviour within a single unit named class, that enhances program design structure and code readability. 
* Class
* Object
* Inheritence
* Polymorphism
* Abstraction
* Encapsulation

### Class
The class is the basic building block of the object oriented program. A class is a template used to create objects and to define object data types and methods.         
A class in java can contain:      
* data member
* method
* constructor
* block
#### Ex program to create a class
```
public class ClassEx { // main class
    public static void main(String[] args){ //main method
        int x = 4;
        int y = 5;
        int c = x+y;
        System.out.println(c);
    }
    
}
```
#### Expected output

>9    
### Object
Object is the basic runtime entity of any object oriented application. They are called as the instance of a class. In reality Objects are the memory location that contains the member data and the methods defined in a class.
#### Ex program to create an object
```
public class Math{
    int x = 7;
    int y = 5;
    void add(){ // method
        System.out.println(x+y);
    }
    public static void main(String[] args){
        Math addition=new Math(); //creating an object
        addition.add();
    }
}  
```
#### Expected output
### Inheritence
In Java classes can be derived from classes. Basically if you need to create a new class and here is already a class that has some of the code you require, then it is possible to derive your new class from the already existing code.            
This concept allows you to reuse the fields and methods of the existing class without rewriting the code in a new class. In this case, Existing class is called super class and the derived class is called the subclass.       
The `extends` keyword is used to perform inheritance in Java
There are few types of Inheritence concepts. let's discuss about it one by one. 
* Single Inheritence
* Multi-level Inheritence
* Hierarchical Inheritence
* Hybrid Inheritence
* Multiple Inheritence(not supported by java).
#### Single Inheritence
In single inheritance, a single subclass extends from a single superclass.
#### Ex program to create an object
```
class Animal {

    String name;

    public void eat() {
        System.out.println("I can eat");
    }
}

class Dog extends Animal { // inherit from Animal

    public void display() { // new method in subclass
        System.out.println("My name is " + name);
    }
}

class Main {
    public static void main(String[] args) {

        // create an object of the subclass
        Dog labrador = new Dog();
        labrador.name = "Tomy";
        labrador.display();
        labrador.eat();
    }
}
```
#### Expected output
>My name is Tomy        
>I can eat
#### Multi-level Inheritence
In multilevel inheritance, a subclass extends from a superclass and then the same subclass acts as a superclass for another class.
#### Ex program to create an object
#### Expected output
#### Hierarchical Inheritence
In hierarchical inheritance, multiple subclasses extend from a single superclass.
#### Ex program to create an object
#### Expected output
#### Hybrid Inheritence
Hybrid inheritance is a combination of two or more types of inheritance.
#### Ex program to create an object
#### Expected output
#### Multiple Inheritence
#### Ex program to create an object
#### Expected output
### Abstraction
Abstraction is the process of hiding implementation details. In other words it is providing the specification for methods.          
Abstraction can be achieved through two methods     
1.Abstract class            
2.Interfaces
#### Ex program to create an object
#### Expected output
### Polymorphism
Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object.
#### Ex program to create an object
#### Expected output
### Encapsulation
The process of binding data and corresponding methods (behavior) together into a single unit is called encapsulation in Java.
#### Ex program to create an object
#### Expected output
