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
 ### Expected output
>java 18.0.1.1 2022-04-22     
>Java(TM) SE Runtime Environment (build 18.0.1.1+2-6)    
>Java HotSpot(TM) 64-Bit Server VM (build 18.0.1.1+2-6, mixed mode, sharing)        
 
 
      javac --version      
### Expected output     
>javac 18.0.1.1

**S-3:** In Visual Studio code install Java extension pack 
(provided by Microsoft)      

<p align="center"><img src="https://github.com/mukesh-techis/Core-Java-/blob/main/img/vscode-java-extension-pack.jpeg?raw=true" width="500" height="200"/> </p>  

***_You are ready to go !!!_***

### Start your first project

**Print** _Hello world_.    


When you save a java program save the file with the extension of .java (i.e) index.java

```
public class index{
   public static void main(String[] args){
   System.out.println("Hello World!");
   }
}
```
### sample output:      
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
