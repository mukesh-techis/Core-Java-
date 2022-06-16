<h1 align="center">Java</h1>
<h3>Introduction to Java</h3>
<span style="font-family:sans-serif; font-size:4em;">  Java is a general purpose high level programming language used to develop various applications. It provides development platforms for various kinds of applications. </span> 
   

<h3>Editions of Java</h3>

* Java2 SE (Standard Edition)
* Java2 EE(Enterprise Edition)
* Java2 ME(Micro Edition)
<h3>To run java in your System:</h3>

**S-1:** install java jdk in your PC based on your Operating System

* [for macOS](https://www.oracle.com/java/technologies/downloads/#jdk18-mac/)
* [for Windows](https://www.oracle.com/java/technologies/downloads/#jdk18-windows)
* [for Linux](https://www.oracle.com/java/technologies/downloads/#jdk18-linux)

**S-2:** check for java version to confirm whether java is successfully installed or not.

In Terminal/command prompt:

      java –-version       
 #### Expected output
>java 18.0.1.1 2022-04-22     
>Java(TM) SE Runtime Environment (build 18.0.1.1+2-6)    
>Java HotSpot(TM) 64-Bit Server VM (build 18.0.1.1+2-6, mixed mode, sharing)        
 
 
      javac --version      
#### Expected output     
>javac 18.0.1.1

**S-3:** In Visual Studio code install Java extension pack 
(provided by Microsoft)      

<p align="center"><img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/vscode-java-extension-pack.jpeg?raw=true" width="500" height="200"/> </p>  

***_You are ready to go !!!_***

### Start your first project

Let us print `Hello World!`
#### Rule to rule Java.
* File Extension: .java (i.e) Index.java
* Main class name and the file name should be the same
* Class names start with an upper case letter
* Method names start with a lower case letter
* Multi-word identifiers are internally capitalized. (i.e) `ageofperson = 18;` can be written as `ageOfPerson = 18;` which is technically said to be camelCase. 
* Use descriptive names for all variables, function names, constants, and other identifiers.

```
public class index{
   public static void main(String[] args){
   System.out.println("Hello World!");
   }
}
```

#### sample output:      
>Hello World!

***_Lets not worry about the methods, syntax and statics., however we’ll be learning those concepts in upcoming topics._***

### Comments in Java      
Java supports single and Multi-line comments          
```
// single line comment

/*      
Multi-line     
comment       
*/      

```      
### Let’s dive a bit deeper into Java Features             
- Object Oriented
- Platform independent
- Simple
- Secure
- Architectural neutral
- Portable
- Robust
- Multi-threaded
- Interpreted
- High Performance
- Distributed
- Dynamic      
### 1.Object Oriented      
Object oriented programming is a methodology that simplifies software development and maintainance by providing some rules.      
- Object
- Class
- Abstraction
- Encapsulation
- Inheritence
- Polymorphism       
### 2.Platform Independent     
Java is platform independent because it follows WORA (Write Once Run Anywhere) concept. The same java program can be executed in different platforms (windows/mac/linux) without making any changes to that program.    
<p align="center"><img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/platform%20independent.png?raw=true"  width="350" /></p>         

### 3.Simple      
Java is designed to be easy to learn. The code is simple and easy to understand        
### 4.Secure           
Java language and Java runtime is designed in such a way that it can’t be invaded from outside.
The byte code that is used for the execution is inspected before execution by Java Runtime Environment(JRE).      
<p align="center"><img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/JREdiff.png?raw=true"  width="350" /></p>         

### 5.Portable       
Being architectural neutral and having no implementation dependent aspects of the specification that makes java portable 

### 6.Robustness (Strong)        
Java is strong because of its two features,              
- Dynamic memory management      
- Runtime error management or Exception handling      
             
### 7.Multi-threaded       
In java it is possible to write programs that can do many tasks simultaneously. This leads to develop smoothly running interactive applications         

### 8.Interpreted    
Java uses both compiler and Interpreter. Java compiler converts the source code into byte codes. These byte codes are then converted into machine code by Interpreter.

### 9.High Performance
Just in time (JIT) compiler is responsible for the high performance of java codes, which compiles the code on-demand basis, that means it compiles only the method which is being called.

### 10.Distributed
Java is distributed because it facilitates users to create distributed applications in java. 

### 11.Dynamic
Java is considered dynamic because of Bytecode. The source code which is written in one platform and that code can be executed in any platform. It loads the class file during runtime only. Hence, any thing that happens in runtime is dynamic.     
### Java Lexical Issues
Java program is a collection of whitespace, identifiers, literals, operators, separators and keywords.
### Whitespace
Java is a free-form programming language which means you need not to follow any special indentation rules.   
```
public class index{public static void main(String[] args){System.out.println("Hello World!");}}     
```
This code can compile and run successfully without any indentation error. However, following indentations is good for code visibility and error handling.      
### Identifiers
Identifiers are nothing but variable names, method names and class names. It can be a combination of uppercase and lowercase , numbers and special characters. It should not begin with a number. 
Ex: name, try4, $sign,etc.       
### Literals
Literals are nothing but the values which the variable holds in java code.    
### Separators
	Separators define the structure of the program. The few separators are parenthesis(), braces{}, period(.), semicolon;, colon:, comma , etc.,       
### Keywords
Keywords are reserved words in java which have specific meaning in it. We cannot use these keywords as variable names, method names and class names.     
<img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/java%20keywords.png?raw=true" />     
### Variables, Operators, Data types, Control Structure      
### Variables in java               
- Local variables          
- Instance variables                
- class/static variables               
### Local variable            
A variable that is declared inside the method is called local variable.          
### Instance variable         
A variable that is declared inside the class but outside the method is called instance variable. It is not declared as static.         
### Static variable        
A variable that is declared as static is known as static variable. It cannot be local.          
```
public class index{
   int data = 50; //instance variable     
   final float pi = 3.14; //final variable      
   static int m = 100; //static variable        
   void method(){
   int n = 90; //local variable
   }
}
```
### Java Data Types
Data types are nothing but reserved memory locations to store values. This means when you create a variable you reserve some space in memory.
There are two data types available in java. They are,    
1. Primitive data types and 
2. Reference/Non-primitive data types 
<p align="center"><img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/datatypes.png?raw=true" /></p>    
There are eight primitive data types that are supported by java. Let us know a bit more about when and where to use it.			
<p align="center"><img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/datatypeTable.png?raw=true" width="600"/></p>		

#### Example program to understand all data types		
		
```
class sample{
	public static void main(String[] args){
		byte b = 100;
		short s = 123;
		int i = 12345;
		long l = 1234567890123L;
		float f = 12.1234F;
		double d = 12.12345123456789;
		boolean bl = true;
		char ch = 'y';
		System.out.println(b);
		System.out.println(s);
		System.out.println(i);
		System.out.println(l);
		System.out.println(f);
		System.out.println(d);
		System.out.println(bl);
		System.out.println(ch);
	}
}	
```		

#### Expected output		
			
>100    
>123    
>12345    
>1234567890123	  
>12.1234    
>12.12345123456789   
>true   
>y   		

### Escape Sequences
There are few escape sequences in java. They are,

<p align="center"><img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/EscapeSeq.png?raw=true" width="400" /></p>

### Operators        	

Operator is a special symbol that is used to perform operations. There are few types of operators in java. Let’s discuss it one by one.	

- Arithmetic operators
- relational operators
- Assignment operators
- Logical operators
- Bitwise operators
- Conditional operators

### Arithmetic Operators
The arithmetic operators are used to perform various arithmetic operations such as algebraic functions. The few Arithmetic operators are +,-,*,/,%,++,-- etc.		
#### Ex program for Arithmetic operators   
```
public class arith {
    public static void main(String[] args){
        int a = 10;
        int b = 20;
        System.out.println("a+b is :"+( a+b));
        System.out.println("b-a is :"+(b+a));
        System.out.println("a*b is :"+(a*b));
        System.out.println("a/b is :"+(b/a));
        System.out.println("a%b is :"+(b%a));
        System.out.println("pre increment of a is :" + (++a));
        System.out.println("post increment of a is :"+ (a++));
        System.out.println("pre decrement of a is :" + (--b));
        System.out.println("post decrement of b is :"+ (b--));
    }   
}			
```	

#### Expected Output 
>a+b is :30	     
>b-a is :30    
>a*b is :200       
>a/b is :2      
>a%b is :0      
>pre increment of a is :11       
>post increment of a is :11        
>pre decrement of a is :19         
>post decrement of b is :19            
		

  
### Relational operators    
Relational operators are used to check the relationship between two operands.
The few relational operators are  == , < , > , <= , >= , != etc.    
#### Ex program for Relational operators   
```
public class relationalex {
    public static void main(String[] args){
        int x = 5;
        int y = 10;
        System.out.println(x == y);
        System.out.println(x != y);
        System.out.println(x > y);
        System.out.println(x < y);
        System.out.println(x >= y);
        System.out.println(x <= y);
    }   
}
```      
#### Expected Output        
>false       
>true          
>false          
>true            
>false      
>true      

### Logical operators
The Logical operators are,    
- AND &&
- OR ||
- NOT !            
#### Ex program for logical operators        
```
public class logicalex {
    public static void main(String[] args){
        boolean a = true;
        boolean b = false;
        System.out.println("a && b = "+ (a&&b));
        System.out.println("a || b = "+(a||b));
        System.out.println("!(a && b) = " + !(a && b));
    }   
}
```            
#### Expected output          
>a && b = false               
>a || b = true              
>!(a && b) = true             

### Assignment operator           
There are following assignment operators supported by java.      
They are = , += , -= , *= , /= , %= , <<= , >>= , &= , ^= , |= etc.           
#### Ex program for assignment operator
```
public class assignex {
    public static void main(String[] args){
        int a = 10;
        int b = 20;
        int c;
        c=a+b;
        System.out.println("c = a+b is "+c);
        c += a;
        System.out.println("c += a is " + c);
        c -= a;
        System.out.println("c -= a is " + c);
        c *= a;
        System.out.println("c *= a is " + c);
        a = 10;
        c = 15;
        c /= a;
        System.out.println("c /= a is " + c);
        a = 10;
        c = 15;
        c %= a;
        System.out.println("c %= a is " + c);
        c <<= 2;
        System.out.println("c <<= 2 is " + c);
        c >>= a;
        System.out.println("c >>= a is " + c);
        c &= a ;
        System.out.println("c &= a is " + c);
        c ^= a;
        System.out.println("c ^= a is " + c);
        c |= a;
        System.out.println("c |= a is " + c);
    }   
}
```                
#### Expected output         
>c = a+b is 30        
>c += a is 40              
>c -= a is 30             
>c *= a is 300             
>c /= a is 1            
>c %= a is 5             
>c <<= 2 is 20             
>c >>= a is 0               
>c &= a is 0               
>c ^= a is 10         
>c |= a is 10           
### Conditional operator(?:)          
Conditional operator is also termed as ternary operator. The Ternary operator is written as,           
`Variable x=(Expression)?value if true:value if false`        
#### Ex program
```
public class condionalEx {
    public static void main(String[] args){
       int a=10;
       String result = a % 2 == 0 ? "Even" : "Odd";
       System.out.println(result);
    }   
}
```
#### Expected output           
>Even

# Control Statements        
Java provides statements that can be used to control the flow of Java code. Such statements are called control statements. It is one of the fundamental features of Java, which provides a smooth flow of program.          
1. Decision making Statements
2. Looping Statements
3. Jump Statements         
### Decision making Statements          
Decision-making statements decide which statement to execute and when. It evaluates the Boolean expression and control the program flow depending upon the result of the condition provided. The few Decision making statements are,     
* Simple if statement
* if-else statement
* else-if ladder
* Nested if-statement
* Switch statement   



### Simple if Statement
If the boolean expression(condition) evaluates to true then the block of code inside the `if` statement will be executed.

#### Ex program `if`

```
public class simpleIf {
    public static void main(String[] args){
        int x = 70;
        if(x>50){
            System.out.println("You are Pass!!!");
        }
    } 
}
 ```
#### Expected output        
> You are Pass!!!

### If...Else Statement

The Java if-else statement also tests the condition. It executes the `if` block if the condition is `true` , otherwise `else` block is executed.

#### Ex program `if...else`

```
public class ifElse {
    public static void main(String[] args){
        int x = 25;
        if(x>50){
            System.out.println("You are Pass!");
        }else{
            System.out.println("You are Fail");
        }
    } 
}
 ```
#### Expected output        
> You are Fail!     

### The else-if ladder

The if-else-if ladder statement executes one condition from multiple statements.

#### Ex program `else-if` ladder

```
public class elseIf {
    public static void main(String[] args) {
        int marks = 75;
        if (marks < 50) {
            System.out.println("fail");
        } else if (marks >= 50 && marks < 60) {
            System.out.println("D grade");
        } else if (marks >= 60 && marks < 70) {
            System.out.println("C grade");
        } else if (marks >= 70 && marks < 80) {
            System.out.println("B grade");
        } else if (marks >= 80 && marks < 90) {
            System.out.println("A grade");
        } else if (marks >= 90 && marks <= 100) {
            System.out.println("S grade");
        } else {
            System.out.println("Invalid!");
        }
    }
}
```
#### Expected output        
> B grade

### Nested-if Statements

Nested if statements mean an if statement inside an if statement. Yes, java allows us to nest if statements within if statements.

#### Ex program `nested-if` condition

```
public class nestedIf {
    public static void main(String[] args) {
        int products = 5;
        int price = 4000;
        if (products >= 5) {
            if (price >= 3000) {
                System.out.println("You are eligible for 50% discount");
            }else{
                System.out.println("You are not eligible for discount");
            }
        }else{
            System.out.println("Purchase minimum 5 products to avail a chance for 50%  off");

        }
    }
}
 ```
#### Expected output        
> You are eligible for 50% discount

### Switch Statements

Nested if statements mean an if statement inside an if statement. Yes, java allows us to nest if statements within if statements.

#### Ex program `switch`

```

```
#### Expected output        
> You are eligible for 50% discount


### Looping Statements
Loops in programming allow a set of instructions to be executed repeatedly until a certain condition is fulfilled. Let's learn about various loops in java.
* `for` loop
* `while` loop
* `do...while` loop

### `For` Loop
A for loop allows you to efficiently run a loop that needs to execute a specific number of times. When you know exactly how many times you want to loop through a block of code, use the for loop instead of a while loop:
#### `for` loop Ex program
```
public class forLoop {
    public static void main(String[] args){
        for(int i=0;i<=5;i++){
            System.out.println(i);
        }
    }  
}
```
#### Expected output
>0      
>1          
>2              
>3              
>4                  
>5                      

### `While` loop
The while loop is a control structure that allows you to repeat a task in certain number of times.
#### Ex program `while` loop
```
public class whileloopEx {
    public static void main(String[] args){
        int x = 10;
        while(x<20){
            System.out.println("value of x:"+x);//try escape sequences here
            x++;
        }
    }   
}
```
#### Expected output
>value of x:10                  
>value of x:11                          
>value of x:12                      
>value of x:13                      
>value of x:14                  
>value of x:15                      
>value of x:16                      
>value of x:17                      
>value of x:18                      
>value of x:19                  
### `Do...While` loop
A `do...while` loop is similar to a while loop, except that a `do...while` loop executes atleast one time
#### Ex program `do...while`
```
public class dowhileEx {
    public static void main(String[] args) {
        int x = 10;
        do{
            System.out.print("value of x:" + x);
            x++;
            System.out.print("\n");
        }while (x < 10);
    } 
}
```
#### Expected output
>value of x:10


##### There is something called *Enhanced for loop.* It is basically of array method so we can learn that concept once we get into array. 

### Jump Statements
1.break             
2.continue

#### Break
The `break` keyword is used to stop the entire loop. It must be used inside the loops or the switch statements.
### Ex program for `break`
```
class breakEx{
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            if (i == 3) {   //using an if condition inside for loop.
                break;
            }
            System.out.println(i);
        }
    }
}
```
#### Expected output
>1                  
>2
### Continue
The continue keyword can be used in any of the loop control structures.It causes to the loop immediately jump to the next iteration of the loop.
#### Ex program `continue`
```
public class continueEx {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            if (i == 3) { // Skip 3 and continue the iteration
                continue;
            }
            System.out.println(i);
        }
    }   
}
```
#### Expected output
> 1             
> 2             
> 4             
> 5                     
