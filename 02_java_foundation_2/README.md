# Java If ... Else
## Java Conditions and If Statements
Java supports the usual logical conditions from mathematics:
- Less than: a < b
- Less than or equal to: a <= b
- Greater than: a > b
- Greater than or equal to: a >= b
- Equal to a == b
- Not Equal to: a != b

You can use these conditions to perform different actions for different decisions.

Java has the following conditional statements:

- Use if to specify a block of code to be executed, if a specified condition is true
- Use else to specify a block of code to be executed, if the same condition is false
- Use else if to specify a new condition to test, if the first condition is false
- Use switch to specify many alternative blocks of code to be executed

# The if Statement
Use the if statement to specify a block of Java code to be executed if a condition is true.

Syntax:

```java 
if (condition) {
  // block of code to be executed if the condition is true
}
 ```

## Example 1

<img width="439" alt="image" src="https://user-images.githubusercontent.com/101321694/164679802-d0370692-b4ad-481a-b496-45c0dd70784d.png">

Output:

<img width="375" alt="image" src="https://user-images.githubusercontent.com/101321694/164680015-8c413859-d625-40c0-a02a-ada76653f0fe.png">

## Example 2

<img width="441" alt="image" src="https://user-images.githubusercontent.com/101321694/164680184-f6cb0980-bff4-461a-852b-c725883b5c67.png">

Output:

<img width="389" alt="image" src="https://user-images.githubusercontent.com/101321694/164680331-1db23482-2a63-41ad-9340-5deb4857b286.png">

# The else Statement

Use the else statement to specify a block of code to be executed if the condition is false.

Syntax:

```java 
if (condition) {
  // block of code to be executed if the condition is true
} else {
  // block of code to be executed if the condition is false
}
 ```

## Example

<img width="426" alt="image" src="https://user-images.githubusercontent.com/101321694/164680728-39ef3e27-52dc-4466-9b22-49cb3b6bcefe.png">

Output:

<img width="361" alt="image" src="https://user-images.githubusercontent.com/101321694/164680858-f0dfc136-ba68-42ba-b84c-3dbefc2a3769.png">


# The else if Statement

Use the else if statement to specify a new condition if the first condition is false.

Syntax:

```java
if (condition1) {
  // block of code to be executed if condition1 is true
} else if (condition2) {
  // block of code to be executed if the condition1 is false and condition2 is true
} else {
  // block of code to be executed if the condition1 is false and condition2 is false
}
```

## Example

<img width="461" alt="image" src="https://user-images.githubusercontent.com/101321694/164681419-52922a3e-b984-48f9-bcdb-fc64489ca8a5.png">

Output:

<img width="394" alt="image" src="https://user-images.githubusercontent.com/101321694/164681544-f2bf8a5a-972a-48f4-9da4-afe33b11a55c.png">

# Short Hand If...Else

There is also a short-hand if else, which is known as the ternary operator because it consists of three operands.
It can be used to replace multiple lines of code with a single line, and is most often used to replace simple if else statements:

Syntax:

```java
variable = (condition) ? expressionTrue : expressionFalse;
```

## Example

<img width="557" alt="image" src="https://user-images.githubusercontent.com/101321694/164684055-8f4b921b-3724-48ad-92a4-94b2c2baa133.png">

Output:

<img width="393" alt="image" src="https://user-images.githubusercontent.com/101321694/164684153-d2e52543-d088-4f68-8d3f-b71bbb714fa6.png">

# Java Switch Statements

Use the switch statement to select one of many code blocks to be executed.

Syntax:

```java
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
 ```

This is how it works:

- The switch expression is evaluated once.
- The value of the expression is compared with the values of each case.
- If there is a match, the associated block of code is executed.

## Example

<img width="458" alt="image" src="https://user-images.githubusercontent.com/101321694/164684653-60cc1e73-365e-4061-87da-f427783759b7.png">

Output:

<img width="405" alt="image" src="https://user-images.githubusercontent.com/101321694/164684743-139d4b31-590c-4f87-a2ec-39ef5eb6cb0a.png">

# The break Keyword

When Java reaches a break keyword, it breaks out of the switch block.
This will stop the execution of more code and case testing inside the block.
When a match is found, and the job is done, it's time for a break. There is no need for more testing.

# The default Keyword

The default keyword specifies some code to run if there is no case match:

## Example

<img width="497" alt="image" src="https://user-images.githubusercontent.com/101321694/164685028-40a42c9a-917d-4ba1-8f0d-6db7b4ab6119.png">

Output:

<img width="344" alt="image" src="https://user-images.githubusercontent.com/101321694/164685111-f3ab25bc-736c-4dfb-a7d0-82297e1d12b4.png">


# Loops

Loops can execute a block of code as long as a specified condition is reached.
Loops are handy because they save time, reduce errors, and they make code more readable.

# Java While Loop

The while loop loops through a block of code as long as a specified condition is true:

Syntax:

```java 
while (condition) {
  // code block to be executed
} 
```
## Example

<img width="431" alt="image" src="https://user-images.githubusercontent.com/101321694/164884128-b041d7c3-b2f5-4e6d-96d6-dcf37a7d1775.png">

Output:

<img width="379" alt="image" src="https://user-images.githubusercontent.com/101321694/164884144-0c83e180-f65d-4155-a7f6-47c2602b8208.png">

# The Do/While Loop

The do/while loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

Syntax:

```java
do {
  // code block to be executed
}
while (condition);
```

The loop will always be executed at least once, even if the condition is false, because the code block is executed before the condition is tested:

## Example

<img width="419" alt="image" src="https://user-images.githubusercontent.com/101321694/164884190-74b41bcf-18f4-44cc-a69a-0f43346834e5.png">

Output:

<img width="378" alt="image" src="https://user-images.githubusercontent.com/101321694/164884206-c0b5e030-fded-4db4-a291-5a1416cc27e8.png">

# Java For Loop

When you know exactly how many times you want to loop through a block of code, use the for loop instead of a while loop:

Syntax:

```java
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
Statement 1 is executed (one time) before the execution of the code block.
Statement 2 defines the condition for executing the code block.
Statement 3 is executed (every time) after the code block has been executed.

## Example 1

<img width="425" alt="image" src="https://user-images.githubusercontent.com/101321694/164884276-f850edaf-4f23-42ce-a262-fbc0ed437469.png">

Output:

<img width="376" alt="image" src="https://user-images.githubusercontent.com/101321694/164884289-ccc6cb66-13e2-4044-8673-f2ace00d2f6a.png">

## Example 2

<img width="465" alt="image" src="https://user-images.githubusercontent.com/101321694/164884304-c591f93c-06ea-47be-be44-aee4974e207c.png">

Output:

<img width="347" alt="image" src="https://user-images.githubusercontent.com/101321694/164884322-c899b246-ae62-4534-87f3-3991cc95b402.png">



# For-Each Loop

There is also a "for-each" loop, which is used exclusively to loop through elements in an array:

Syntax:

```java 
for (type variableName : arrayName) {
  // code block to be executed
}
```

## Example

<img width="466" alt="image" src="https://user-images.githubusercontent.com/101321694/164884362-60fea6c3-2721-4a39-9af6-3ea8b4cef676.png">

Output:

<img width="380" alt="image" src="https://user-images.githubusercontent.com/101321694/164884373-d6f9c8c0-658a-4013-87ae-21095a44ff45.png">

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


























