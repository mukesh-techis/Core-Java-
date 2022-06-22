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
public class model{
  int x = 5;
}
```
### Object
Object is the basic runtime entity of any object oriented application. They are called as the instance of a class. In reality Objects are the memory location that contains the member data and the methods defined in a class.
#### Ex program to create an object
```
class Student{  
 int id;  
 String name;  
}  
class TestStudent2{  
 public static void main(String args[]){  
  Student s1=new Student();  
  s1.id=101;  
  s1.name="Sonoo";  
  System.out.println(s1.id+" "+s1.name);//printing members with a white space  
 }  
}  
```
### Inheritence
In Java classes can be derived from classes. Basically if you need to create a new class and here is already a class that has some of the code you require, then it is possible to derive your new class from the already existing code.
This concept allows you to reuse the fields and methods of the existing class without rewriting the code in a new class. In this case, Existing class is called super class and the derived class is called the subclass.
### Abstraction
Abstraction is the process of hiding implementation details. In other words it is providing the specification for methods.          
Abstraction can be achieved through two methods     
1.Abstract class
2.Interfaces
### Polymorphism
Polymorphism is the ability of an object to take on many forms. The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object.
### Encapsulation
The process of binding data and corresponding methods (behavior) together into a single unit is called encapsulation in Java.
