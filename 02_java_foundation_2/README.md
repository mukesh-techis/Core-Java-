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

# Java Break

You have already seen the break statement used in an earlier chapter of this tutorial. It was used to "jump out" of a switch statement.
The break statement can also be used to jump out of a loop.

This example stops the loop when i is equal to 4:

## Example:

<img width="435" alt="image" src="https://user-images.githubusercontent.com/101321694/164960050-f210d8c8-9ba5-443f-8bc1-a4107e3f4f67.png">

Output:

<img width="338" alt="image" src="https://user-images.githubusercontent.com/101321694/164960132-a35a0630-1513-44d3-942c-6b5b1c06cd4e.png">


# Java Continue

The continue statement breaks one iteration (in the loop), if a specified condition occurs, and continues with the next iteration in the loop.
This example skips the value of 4:


## Example:

<img width="422" alt="image" src="https://user-images.githubusercontent.com/101321694/164960168-6bd977a5-19ac-4cc0-9766-208f3851d2c2.png">

Output:

<img width="388" alt="image" src="https://user-images.githubusercontent.com/101321694/164960225-81c0b6ff-9039-4b3f-82d0-ab47575cbc96.png">


# Break and Continue in While Loop

You can also use break and continue in while loops:

## Break Example

## Example:

<img width="380" alt="image" src="https://user-images.githubusercontent.com/101321694/164960258-e90b565f-8064-4da7-addd-6dca9c288f6e.png">

Output:

<img width="361" alt="image" src="https://user-images.githubusercontent.com/101321694/164960281-68609ff0-d7f3-4cae-b8c5-9f09742d7f5c.png">

## Continue Example

<img width="400" alt="image" src="https://user-images.githubusercontent.com/101321694/164960310-b15c814e-773e-439b-8716-07d272738dc6.png">

Output:

<img width="348" alt="image" src="https://user-images.githubusercontent.com/101321694/164960327-6208fa30-bb37-4ed7-9186-9ac37426ebb7.png">


# Java Arrays
Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.
To declare an array, define the variable type with square brackets:

```java
String[] cars;
```

We have now declared a variable that holds an array of strings. To insert values to it, we can use an array literal - place the values in a comma-separated list, inside curly braces:

```java 
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
```

To create an array of integers, you could write:
```java 
int[] myNum = {10, 20, 30, 40};
```


# Access the Elements of an Array

You access an array element by referring to the index number.
This statement accesses the value of the first element in cars:


## Example

<img width="440" alt="image" src="https://user-images.githubusercontent.com/101321694/164960415-b4834305-78eb-41e1-892b-f41d3c5d6932.png">

Output:

<img width="345" alt="image" src="https://user-images.githubusercontent.com/101321694/164960511-16800ea4-43b5-407f-85dd-89c05bcf3f66.png">


# Change an Array Element

To change the value of a specific element, refer to the index number:

```java 
cars[0] = "Opel";
```

## Example:

<img width="447" alt="image" src="https://user-images.githubusercontent.com/101321694/164960577-73bc9ba0-526a-49ee-80c2-feabb9414e8c.png">

Output:

<img width="364" alt="image" src="https://user-images.githubusercontent.com/101321694/164960709-0ff67785-619c-4673-b8f4-ce5205c8f8c6.png">


# Array Length

To find out how many elements an array has, use the length property:

## Example

<img width="442" alt="image" src="https://user-images.githubusercontent.com/101321694/164960738-c2b85bcc-b27a-4b37-9a54-d010d540af74.png">

Output:

<img width="361" alt="image" src="https://user-images.githubusercontent.com/101321694/164960767-64fceece-8599-4c39-9408-90dc6848a6e6.png">

# Loop Through an Array

You can loop through the array elements with the for loop, and use the length property to specify how many times the loop should run.

The following example outputs all elements in the cars array:

## Example:

<img width="408" alt="image" src="https://user-images.githubusercontent.com/101321694/164960795-d7442b90-6dae-4e2a-9de6-f52c2cce7e8a.png">

Output:

<img width="356" alt="image" src="https://user-images.githubusercontent.com/101321694/164960812-d75a9be8-6997-4913-aada-f6346116380c.png">


# Loop Through an Array with For-Each

There is also a "for-each" loop, which is used exclusively to loop through elements in arrays:

Syntax:

```java
for (type variableName : arrayName) {
  // code block to be executed
}

```

## Example:

<img width="464" alt="image" src="https://user-images.githubusercontent.com/101321694/164960862-eabf9834-02cd-4b7b-9de6-1e2da1533258.png">

Output:

<img width="380" alt="image" src="https://user-images.githubusercontent.com/101321694/164960883-e884d98b-111e-44aa-aebc-d1e803d03e20.png">


# Multidimensional Arrays

A multidimensional array is an array of arrays.
To create a two-dimensional array, add each array within its own set of curly braces:
```java 
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
```
myNumbers is now an array with two arrays as its elements.
To access the elements of the myNumbers array, specify two indexes: one for the array, and one for the element inside that array. This example accesses the third element (2) in the second array (1) of myNumbers:

## Example:

<img width="419" alt="image" src="https://user-images.githubusercontent.com/101321694/164960923-ef33c9c8-c2db-432f-b4f7-e3b27c400da1.png">

Output:

<img width="336" alt="image" src="https://user-images.githubusercontent.com/101321694/164960940-51f4154e-b455-4d21-9a35-03278d0a29d6.png">

We can also use a for loop inside another for loop to get the elements of a two-dimensional array (we still have to point to the two indexes):

## Example:

<img width="461" alt="image" src="https://user-images.githubusercontent.com/101321694/164960962-27265b9f-edb9-41a4-b312-e25c6316d260.png">

Output:

<img width="342" alt="image" src="https://user-images.githubusercontent.com/101321694/164960984-c9f53653-4381-4940-8acd-2b2a5f2f8d07.png">

# Java Methods

A method is a block of code which only runs when it is called.
You can pass data, known as parameters, into a method.
Methods are used to perform certain actions, and they are also known as functions.
Why use methods? To reuse code: define the code once, and use it many times.

## Create a Method

A method must be declared within a class. It is defined with the name of the method, followed by parentheses (). Java provides some pre-defined methods, such as System.out.println(), but you can also create your own methods to perform certain actions:

Syntax:
```java
public class Main {
  static void myMethod() {
    // code to be executed
  }
}
```

- myMethod() is the name of the method
- static means that the method belongs to the Main class and not an object of the Main class. You will learn more about objects and how to access methods   through objects later in this tutorial.
- void means that this method does not have a return value. You will learn more about return values later in this chapter

# Call a Method

To call a method in Java, write the method's name followed by two parentheses () and a semicolon;
In the following example, myMethod() is used to print a text (the action), when it is called:

## Example:

<img width="412" alt="image" src="https://user-images.githubusercontent.com/101321694/164961833-cd99287d-4fa0-486b-94ab-e03e95e3bbcd.png">

Output:

<img width="342" alt="image" src="https://user-images.githubusercontent.com/101321694/164962125-8df807f0-4c14-4a79-a6ae-82bda2540ddf.png">

# Java Method Parameters

## Parameters and Arguments
Information can be passed to methods as parameter. Parameters act as variables inside the method.
Parameters are specified after the method name, inside the parentheses. You can add as many parameters as you want, just separate them with a comma.
The following example has a method that takes a String called fname as parameter. When the method is called, we pass along a first name, which is used inside the method to print the full name:

## Example:

<img width="428" alt="image" src="https://user-images.githubusercontent.com/101321694/164963078-3425e67a-8cd7-4fe7-89b3-3d89a3aaff15.png">

Output:

<img width="355" alt="image" src="https://user-images.githubusercontent.com/101321694/164963313-7ff45248-99c1-4985-9a52-1d1ca697254e.png">

## Multiple Parameters:
You can have as many parameters as you like:

## Example:

<img width="427" alt="image" src="https://user-images.githubusercontent.com/101321694/164963657-9d82b1fe-6cc8-467b-b166-e48a81923fd1.png">

Output:

<img width="362" alt="image" src="https://user-images.githubusercontent.com/101321694/164963991-3e9daf50-2fcc-4599-bd8a-37704c6223bc.png">

# Return Values

The void keyword, used in the examples above, indicates that the method should not return a value. If you want the method to return a value, you can use a primitive data type (such as int, char, etc.) instead of void, and use the return keyword inside the method:

## Example 1:

<img width="401" alt="image" src="https://user-images.githubusercontent.com/101321694/164964567-9ded8a26-5bf1-4732-b736-9acc42e2fc4f.png">

Output:

<img width="341" alt="image" src="https://user-images.githubusercontent.com/101321694/164964585-4be09bbe-33ba-4b27-afa3-a23fa2530aaa.png">

## Example 2:

<img width="384" alt="image" src="https://user-images.githubusercontent.com/101321694/164964609-15603e5f-a7bc-493a-bf8d-72c0143a55cf.png">

Output:

<img width="362" alt="image" src="https://user-images.githubusercontent.com/101321694/164964640-c6aab60e-9be1-4a28-9dbb-b2adf450f14e.png">


You can also store the result in a variable (recommended, as it is easier to read and maintain):
## Example:

<img width="394" alt="image" src="https://user-images.githubusercontent.com/101321694/164965244-967e5b59-354b-4535-a94a-91ac23a69cab.png">

Output:

<img width="357" alt="image" src="https://user-images.githubusercontent.com/101321694/164965277-92205a9b-ac28-42a1-86cc-58e47ca10f9b.png">


# A Method with If...Else

It is common to use if...else statements inside methods:

## Example:

<img width="591" alt="image" src="https://user-images.githubusercontent.com/101321694/164965333-28a1351c-2049-4e80-abc0-2a8901212ddc.png">

Output:

<img width="336" alt="image" src="https://user-images.githubusercontent.com/101321694/164965353-ab13fc7d-77c0-4406-b16c-57d0f08b5c65.png">

# Method Overloading

With method overloading, multiple methods can have the same name with different parameters:

## Example:

```java 
int myMethod(int x)
float myMethod(float x)
double myMethod(double x, double y)
```

Instead of defining two methods that should do the same thing, it is better to overload one.
In the example below, we overload the plusMethod method to work for both int and double:

## Example:

<img width="423" alt="image" src="https://user-images.githubusercontent.com/101321694/164965409-97a8595b-627d-4dd6-9ebd-cecef15ab10e.png">

Output:

<img width="338" alt="image" src="https://user-images.githubusercontent.com/101321694/164965440-ea498181-4f4c-4d95-baa6-cd2e70e9d2a3.png">

# Java Scope

In Java, variables are only accessible inside the region they are created. This is called scope.

## Method Scope

Variables declared directly inside a method are available anywhere in the method following the line of code in which they were declared:

## Example:
```java
public class Main {
  public static void main(String[] args) {

    // Code here CANNOT use x

    int x = 100;

    // Code here can use x
    System.out.println(x);
  }
}
```



# Block Scope

A block of code refers to all of the code between curly braces {}.
Variables declared inside blocks of code are only accessible by the code between the curly braces, which follows the line in which the variable was declared:

## Example:
```java
public class Main {
  public static void main(String[] args) {

    // Code here CANNOT use x

    { // This is a block

      // Code here CANNOT use x

      int x = 100;
      // Code here CAN use x
      System.out.println(x);

   } // The block ends here

  // Code here CANNOT use x

  }
}
```

# Java Recursion

Recursion is the technique of making a function call itself. This technique provides a way to break complicated problems down into simple problems which are easier to solve.
Recursion may be a bit difficult to understand. The best way to figure out how it works is to experiment with it.
Recursion Example
Adding two numbers together is easy to do, but adding a range of numbers is more complicated. In the following example, recursion is used to add a range of numbers together by breaking it down into the simple task of adding two numbers:

## Example:

Use recursion to add all of the numbers up to 10.

<img width="373" alt="image" src="https://user-images.githubusercontent.com/101321694/164965580-fbfc07b8-33be-44ef-adfd-0f5b3fd164c6.png">



# Halting Condition

Just as loops can run into the problem of infinite looping, recursive functions can run into the problem of infinite recursion. Infinite recursion is when the function never stops calling itself. Every recursive function should have a halting condition, which is the condition where the function stops calling itself. In the previous example, the halting condition is when the parameter k becomes 0.
It is helpful to see a variety of different examples to better understand the concept. In this example, the function adds a range of numbers between a start and an end. The halting condition for this recursive function is when end is not greater than start:

## Example

Use recursion to add all of the numbers between 5 to 10.

<img width="444" alt="image" src="https://user-images.githubusercontent.com/101321694/164965612-507fd6cb-8864-4568-b036-a1318e0c7346.png">


























