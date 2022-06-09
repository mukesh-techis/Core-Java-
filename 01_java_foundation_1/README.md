Java
Introduction to java
(Everything in java is an Object)

	Java is a general purpose high level programming language used to develop various applications. It provides development platforms for various kinds of applications.
Editions of java
Java2 SE (Standard Edition)
Java2 EE(Enterprise Edition)
Java2 ME(Micro Edition)


Java is one of the most popular languages in the coding world! It is owned by Oracle, and more than 3 billion devices run Java.
It is used for:
* Mobile applications (specially Android apps)
* Desktop applications
* Web applications
* Web servers and application servers
* Games
* Database connection
* And much, much more!

<h2>Why Use Java?</h2>

* Java works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc.)
* It is one of the most popular programming language in the world
* It is easy to learn and simple to use
* It is open-source and free
* It is secure, fast and powerful
* It has a huge community support (tens of millions of developers)
* Java is an object oriented language which gives a clear structure to programs and allows code to be reused, lowering development costs.

<h3>Getting Started </h3>

We will be using JDoodle online compiler to learn coding in java. You don’t have to install anything on your system.

<h3>Hello World</h3>

System.out.println() is used to print something on the computer screen.

Write the following code in the Jdoodle compiler and press execute.

![Screenshot 2022-04-21 at 1 50 08 PM](https://user-images.githubusercontent.com/100328396/164412746-8612b915-4b68-446d-9523-5190e98f2a13.png)

Don't worry if you don't understand the code above - we will discuss it in detail in later chapters. For now, focus on how to run the code above.
The output should be:

![Screenshot 2022-04-21 at 1 50 08 PM](https://user-images.githubusercontent.com/100328396/164413136-335e3465-a33a-486e-bdf4-1ca8f1ea35ee.png)

Congratulations! You have written and executed your first Java program.

<h4>Java Syntax</h4>

Syntax basically means the correct structure to write code in Java.

![Screenshot 2022-04-21 at 1 50 08 PM](https://user-images.githubusercontent.com/100328396/164413593-63b5a393-179e-445d-a317-c0d408b6f3c0.png)

<p>Every line of code that runs in Java must be inside a class. In our example, we named the class Main. A class should always start with an uppercase first letter.</p>
<p>Note: Java is case-sensitive: "MyClass" and "myclass" has different meaning.</p>

The name of the java file must match the class name.

<h4> The main method </h4>

The main() method is required and you will see it in every Java program:

![Screenshot 2022-04-21 at 8 51 56 PM](https://user-images.githubusercontent.com/100328396/164491570-81715b34-78c8-42ef-8f8a-4d66bce44f5a.png)

<p>Any code inside the main() method will be executed. Don't worry about the keywords before and after main. You will get to know them bit by bit while learning Java.</p>
For now, just remember that every Java program has a class name which must match the filename, and that every program must contain the main() method.

<h4> System.out.println() </h4>

Inside the main() method, we can use the println() method to print a line of text to the screen:

![Screenshot 2022-04-21 at 8 53 57 PM](https://user-images.githubusercontent.com/100328396/164491963-a80666c3-b895-4342-995a-02e7bcc4031a.png)

<p>Note: The curly braces {} marks the beginning and the end of a block of code.</p>
<p>System is a built-in Java class that contains useful members, such as out, which is short for "output". The println() method, short for "print line", is used to print a value to the screen (or a file).</p>
<p>Don't worry too much about System, out and println(). Just know that you need them together to print stuff to the screen.</p>

You should also note that each code statement must end with a semicolon (;).

You can add as many println() methods as you want. Note that it will add a new line for each method:

![Screenshot 2022-04-21 at 9 00 02 PM](https://user-images.githubusercontent.com/100328396/164494814-48b9cebd-5121-4b0f-96e4-1b4a649a0205.png)

Output:

![Screenshot 2022-04-21 at 9 01 09 PM](https://user-images.githubusercontent.com/100328396/164495485-f235f12f-6a9b-4055-bcdf-50323338f9d5.png)

You can also output numbers, and perform mathematical calculations:

![Screenshot 2022-04-21 at 9 02 06 PM](https://user-images.githubusercontent.com/100328396/164496069-411b4a27-4d4a-4dc6-a57a-e666056840d8.png)

Note that we don't use double quotes ("") inside println() to output numbers.


Output:

![Screenshot 2022-04-21 at 9 08 22 PM](https://user-images.githubusercontent.com/100328396/164498067-eb63668f-c2d2-4b72-94bf-5a4b4d2f4f41.png)



There is also a print() method, which is similar to println().

The only difference is that it does not insert a new line at the end of the output:

![Screenshot 2022-04-21 at 9 05 26 PM](https://user-images.githubusercontent.com/100328396/164497468-93d65590-0a95-4eac-a5ef-e4274288e6c5.png)


Output:

![Screenshot 2022-04-21 at 9 06 06 PM](https://user-images.githubusercontent.com/100328396/164497612-1cd64ed3-d90c-4be8-b407-653a05d9d93e.png)

<h3>Java Comments</h3>

Comments can be used to explain Java code, and to make it more readable. It can also be used to prevent execution when testing alternative code.

<h4>Single-line Comments</h4>

Single-line comments start with two forward slashes (//).

Any text between // and the end of the line is ignored by Java (will not be executed).

This example uses a single-line comment before a line of code:

![Screenshot 2022-04-21 at 9 10 33 PM](https://user-images.githubusercontent.com/100328396/164498534-c9393c36-7c29-420c-b6a3-43d4af8dc026.png)

Output:

![Screenshot 2022-04-21 at 9 11 18 PM](https://user-images.githubusercontent.com/100328396/164498682-3ae0be73-c4d5-4dbf-b815-5e766c2bc127.png)

<h3>Java Multi-line Comments</h3>

Multi-line comments start with /* and ends with */.

Any text between /* and */ will be ignored by Java.


Ths example uses a multi-line comment (a comment block) to explain the code:

![Screenshot 2022-04-21 at 9 15 25 PM](https://user-images.githubusercontent.com/100328396/164499527-7c669d67-5540-417d-a12a-fd75366a6e8e.png)

Output:

![Screenshot 2022-04-21 at 9 15 54 PM](https://user-images.githubusercontent.com/100328396/164499629-92190eb5-7ed1-40bb-b20b-4bb88448a6c9.png)

Single or multi-line comments?

It is up to you which you want to use. Normally, we use // for short comments, and /* */ for longer.

<h3>Java Variables</h3>

Variables are containers for storing data values.

In Java, there are different types of variables, for example:

* String - stores text, such as "Hello". String values are surrounded by double quotes
* int - stores integers (whole numbers), without decimals, such as 123 or -123
* float - stores floating point numbers, with decimals, such as 19.99 or -19.99
* char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
* boolean - stores values with two states: true or false

<h4>Declaring (Creating) Variables</h4>

To create a variable, you must specify the type and assign it a value:

Syntax:

<i>type variableName=value</i>

Where type is one of Java's types (such as int or String), and variableName is the name of the variable (such as x or name). The equal sign is used to assign values to the variable.

The general rules for naming variables are:

* Names can contain letters, digits, underscores, and dollar signs
* Names must begin with a letter
* Names should start with a lowercase letter and it cannot contain whitespace
* Names can also begin with $ and _ (but we will not use it in this tutorial)
* Names are case sensitive ("myVar" and "myvar" are different variables)
* Reserved words (like Java keywords, such as int or boolean) cannot be used as names

To create a variable that should store text, look at the following example:

Create a variable called name of type String and assign it the value "John":

![Screenshot 2022-04-21 at 9 21 28 PM](https://user-images.githubusercontent.com/100328396/164500710-54eda021-c52f-4c04-baa3-7f7eac820d4c.png)

Output:

![Screenshot 2022-04-21 at 9 22 05 PM](https://user-images.githubusercontent.com/100328396/164500848-5a29c1e7-d70a-4753-bb8f-b7bdd7715099.png)

To create a variable that should store a number, look at the following example:

![Screenshot 2022-04-21 at 9 22 51 PM](https://user-images.githubusercontent.com/100328396/164501022-9f1cdd60-1a67-409a-930a-a36c779440a0.png)

Output:

![Screenshot 2022-04-21 at 9 23 39 PM](https://user-images.githubusercontent.com/100328396/164501171-836d0e66-0896-488c-b563-ad2f4c667a8c.png)

You can also declare a variable without assigning the value, and assign the value later:

![Screenshot 2022-04-21 at 9 24 19 PM](https://user-images.githubusercontent.com/100328396/164501295-8dfd190a-e8ce-419c-9de0-e2f84a401dad.png)

Output:

![Screenshot 2022-04-21 at 9 24 57 PM](https://user-images.githubusercontent.com/100328396/164501425-7f6d4193-828f-459b-8cae-c908931acebe.png)

Note that if you assign a new value to an existing variable, it will overwrite the previous value:

![Screenshot 2022-04-21 at 9 25 54 PM](https://user-images.githubusercontent.com/100328396/164501619-365ca8f5-21d0-4365-9741-da13841c2072.png)

Output:

![Screenshot 2022-04-21 at 9 26 21 PM](https://user-images.githubusercontent.com/100328396/164501702-954f5a30-9b1f-4fcd-9a04-5b41d8646e2a.png)

<h3>Final Variables</h3>

If you don't want others (or yourself) to overwrite existing values, use the final keyword (this will declare the variable as "final" or "constant", which means unchangeable and read-only):

![Screenshot 2022-04-21 at 9 29 57 PM](https://user-images.githubusercontent.com/100328396/164502333-4a351be6-d76d-49fb-ae54-8e48657c8ed3.png)

Output:

![Screenshot 2022-04-21 at 9 30 42 PM](https://user-images.githubusercontent.com/100328396/164502480-b2769e43-a9c5-4dfc-99a2-0e27766e6206.png)

 
A demonstration of how to declare variables of other types:

![Screenshot 2022-04-21 at 9 31 22 PM](https://user-images.githubusercontent.com/100328396/164502612-73313328-bf0f-40f5-b30f-69716a99e489.png)

You can also use the + character to add a variable to another variable:

![Screenshot 2022-04-21 at 9 32 03 PM](https://user-images.githubusercontent.com/100328396/164502755-687b9c85-2a5e-4fe4-bac2-de285f6ca529.png)

Output:

![Screenshot 2022-04-21 at 9 32 47 PM](https://user-images.githubusercontent.com/100328396/164502898-8f491c3f-31ff-449c-9fe1-86b962afffc4.png)

Declare Many Variables

To declare more than one variable of the same type, you can use a comma-separated list:

Instead of writing:

![Screenshot 2022-04-21 at 9 33 35 PM](https://user-images.githubusercontent.com/100328396/164503072-19d3670a-4d72-44a4-8885-677e7d62cc05.png)

We could write:

![Screenshot 2022-04-21 at 9 34 17 PM](https://user-images.githubusercontent.com/100328396/164503206-0088861e-fb49-4fcd-9d95-59593afa434b.png)

We can also assign the same value to multiple variables in one line:

![Screenshot 2022-04-21 at 9 35 15 PM](https://user-images.githubusercontent.com/100328396/164503367-f658b0a7-978d-413a-9bfc-1c7039eebf82.png)

<h3>Java Data Types</h3>


Data types are divided into two groups:
* Primitive data types - includes byte, short, int, long, float, double, boolean and char
* Non-primitive data types - such as String, Arrays and Classes (you will learn more about these in a later chapter)

<h4>Primitive Data Types</h4>

A primitive data type specifies the size and type of variable values, and it has no additional methods.

There are eight primitive data types in Java:

![Screenshot 2022-04-21 at 9 36 55 PM](https://user-images.githubusercontent.com/100328396/164503679-693f9a53-39a2-4cf8-bc6e-dcf25f8a92aa.png)


Even though there are many numeric types in Java, the most used for numbers are int (for whole numbers) and double (for floating point numbers).

<h4>Integer Types</h4>

<h5>Byte</h5>

The byte data type can store whole numbers from -128 to 127. This can be used instead of int or other integer types to save memory when you are certain that the value will be within -128 and 127:

![Screenshot 2022-04-21 at 9 39 57 PM](https://user-images.githubusercontent.com/100328396/164504212-772fba75-e63f-40c7-a11b-fcab0a7c176f.png)

<h5>Short</h5>

The short data type can store whole numbers from -32768 to 32767:

![Screenshot 2022-04-21 at 9 43 23 PM](https://user-images.githubusercontent.com/100328396/164504825-56a3eb03-407f-4c38-a605-4237434019f9.png)

<h5>Int</h5>

The int data type can store whole numbers from -2147483648 to 2147483647. In general, and in our tutorial, the int data type is the preferred data type when we create variables with a numeric value.

![Screenshot 2022-04-21 at 9 44 11 PM](https://user-images.githubusercontent.com/100328396/164504965-42cd7d41-4777-4027-b347-c784270e14e2.png)


<h5>Long</h5>

The long data type can store whole numbers from -9223372036854775808 to 9223372036854775807. This is used when int is not large enough to store the value. Note that you should end the value with an "L":

![Screenshot 2022-04-21 at 9 44 59 PM](https://user-images.githubusercontent.com/100328396/164505112-849c34d4-ffe7-4287-a77e-6b8f20cd839b.png)

<h4>Floating Point Types</h4>

You should use a floating point type whenever you need a number with a decimal, such as 9.99 or 3.14515.

<h5>Float</h5>

The float data type can store fractional numbers from 3.4e−038 to 3.4e+038. <p>Note that you should end the value with an "f":</p>

![Screenshot 2022-04-21 at 9 48 22 PM](https://user-images.githubusercontent.com/100328396/164505717-633a72f2-4840-43e1-a773-72ec59ea0017.png)

<h5>Double</h5>

The double data type can store fractional numbers from 1.7e−308 to 1.7e+308. Note that you should end the value with a "d":

![Screenshot 2022-04-21 at 9 49 15 PM](https://user-images.githubusercontent.com/100328396/164505867-124b81f3-af6d-4570-80ac-a42ac5edfa9a.png)

<h5>Use float or double?</h5>

The precision of a floating point value indicates how many digits the value can have after the decimal point. The precision of float is only six or seven decimal digits, while double variables have a precision of about 15 digits. Therefore it is safer to use double for most calculations.

<h5>Boolean Types</h5>

A boolean data type is declared with the boolean keyword and can only take the values true or false:

![Screenshot 2022-04-21 at 9 50 40 PM](https://user-images.githubusercontent.com/100328396/164506128-8e70d5f9-7188-4f2f-bedb-94067075244f.png)

Boolean values are mostly used for conditional testing, which you will learn more about in a later chapter.

<h5>Characters</h5>

The char data type is used to store a single character. The character must be surrounded by single quotes, like 'A' or 'c':

![Screenshot 2022-04-21 at 9 51 41 PM](https://user-images.githubusercontent.com/100328396/164506290-36d112ad-1dcf-4560-8b57-e6fe01a4749d.png)

<h5>Strings</h5>

The String data type is used to store a sequence of characters (text). String values must be surrounded by double quotes:

![Screenshot 2022-04-21 at 9 52 31 PM](https://user-images.githubusercontent.com/100328396/164506464-f6f8f777-ac2f-488d-a16b-4bb094db6065.png)

The String type is so much used and integrated in Java, that some call it "the special ninth type".

A String in Java is actually a non-primitive data type, because it refers to an object. The String object has methods that are used to perform certain operations on strings. Don't worry if you don't understand the term "object" just yet. We will learn more about strings and objects in a later chapter.

<h3>Non-Primitive Data Types</h3>


Non-primitive data types are called reference types because they refer to objects.


The main difference between primitive and non-primitive data types are:

* Primitive types are predefined (already defined) in Java. Non-primitive types are created by the programmer and is not defined by Java (except for String).
* Non-primitive types can be used to call methods to perform certain operations, while primitive types cannot.
* A primitive type has always a value, while non-primitive types can be null.
* A primitive type starts with a lowercase letter, while non-primitive types starts with an uppercase letter.
* The size of a primitive type depends on the data type, while non-primitive types have all the same size.
 

Examples of non-primitive types are String, Arrays, Classes, Interface, etc. You will learn more about these in a later chapter.


<h3>Java Type Casting</h3>

Type casting is when you assign a value of one primitive data type to another type.

In Java, there are two types of casting:

* Widening Casting (automatically) - converting a smaller type to a larger type size
byte -> short -> char -> int -> long -> float -> double

* Narrowing Casting (manually) - converting a larger type to a smaller size 
type
double -> float -> long -> int -> char -> short -> byte
<h4>Widening Casting</h4>

Widening casting is done automatically when passing a smaller size type to a larger size type:

![Screenshot 2022-04-21 at 9 56 37 PM](https://user-images.githubusercontent.com/100328396/164507117-43897878-6c34-42a0-912d-568696ccf36c.png)

<h4>Narrow Casting</h4>

Narrowing casting must be done manually by placing the type in parentheses in front of the value:

![Screenshot 2022-04-21 at 9 57 41 PM](https://user-images.githubusercontent.com/100328396/164507274-f79650cf-694d-4692-81c2-fee90ce04fed.png)

<h3>Operators</h3>

Java divides the operators into the following groups:

* Arithmetic operators
* Assignment operators
* Comparison operators
* Logical operators
*bBitwise operators
 
<h4>Arithmetic Operators</h4>

Arithmetic operators are used to perform common mathematical operations.

![Screenshot 2022-04-21 at 9 59 18 PM](https://user-images.githubusercontent.com/100328396/164507525-10a7905a-07f6-40f0-9c66-2373e2a42e05.png)

<h4>Java Assignment Operators</h4>

Assignment operators are used to assign values to variables.

In the example below, we use the assignment operator (=) to assign the value 10 to a variable called x:

![Screenshot 2022-04-21 at 10 00 28 PM](https://user-images.githubusercontent.com/100328396/164507729-fa975490-dc5f-4653-8140-67bc460b2bcd.png)

The addition assignment operator (+=) adds a value to a variable and then assigns it to the variable:

![Screenshot 2022-04-21 at 10 01 05 PM](https://user-images.githubusercontent.com/100328396/164507844-6915d10d-b5df-4982-af91-1a47578bb31d.png)

![Screenshot 2022-04-21 at 10 01 59 PM](https://user-images.githubusercontent.com/100328396/164508000-70480fe3-bd93-4a17-a232-bfafea4607d7.png)


<h4>Java Comparison Operators</h4>

Comparison operators are used to compare two values:

![Screenshot 2022-04-21 at 10 02 58 PM](https://user-images.githubusercontent.com/100328396/164508133-eb73c71a-3059-4f85-aa99-99d205d280d0.png)

<h4>Java Logical Operators</h4>

Logical operators are used to determine the logic between variables or values:

![Screenshot 2022-04-21 at 10 03 46 PM](https://user-images.githubusercontent.com/100328396/164508275-c772247e-afb9-4326-a969-463bef4b0538.png)

<h3>Java Strings</h3>

Strings are used for storing text. A String variable contains a collection of characters surrounded by double quotes:

![Screenshot 2022-04-21 at 10 04 35 PM](https://user-images.githubusercontent.com/100328396/164508425-8aca1f6b-27d2-447b-80c2-561f932ef84c.png)

<h4>String Length</h4>

A String in Java is actually an object, which contains methods that can perform certain operations on strings. For example, the length of a string can be found with the length() method:

![Screenshot 2022-04-21 at 10 05 44 PM](https://user-images.githubusercontent.com/100328396/164508653-4adeadf8-6acd-43d8-a779-1397d2eed281.png)

<h4>More String Methods</h4>

There are many string methods available, for example toUpperCase() and toLowerCase():


![Screenshot 2022-04-21 at 10 07 15 PM](https://user-images.githubusercontent.com/100328396/164508903-74c06828-1923-4f49-b353-69fb6b6dd18d.png)

<h4>Finding a Character in a String</h4>

The indexOf() method returns the index (the position) of the first occurrence of a specified text in a string (including whitespace):

![Screenshot 2022-04-21 at 10 08 02 PM](https://user-images.githubusercontent.com/100328396/164509024-e69b2777-bb76-4bcd-9098-a84e4e5bb356.png)

<h4>String Concatenation</h4>

In Java we can perform concatenation with either the ‘+’ operator or the concat() function.

![Screenshot 2022-04-21 at 10 08 47 PM](https://user-images.githubusercontent.com/100328396/164509144-0005ba24-648b-44e0-96e0-1ba869143931.png)

Both methods give us the same output:

![Screenshot 2022-04-21 at 10 09 19 PM](https://user-images.githubusercontent.com/100328396/164509243-2d87bb1b-b9b7-420f-a271-f575ecd6b1b3.png)

<h4>Numbers and strings</h4>

If you add two numbers, the result will be a number:

![Screenshot 2022-04-21 at 10 10 17 PM](https://user-images.githubusercontent.com/100328396/164509405-17e14a51-e454-406a-a4ef-e766a4dadf96.png)

If you add two strings, the result will be a string concatenation:

![Screenshot 2022-04-21 at 10 11 01 PM](https://user-images.githubusercontent.com/100328396/164509538-74c4b861-e2d0-4d08-88c1-6b66f545fc0d.png)

 
If you add a number and a string, the result will be a string concatenation:


![Screenshot 2022-04-21 at 10 11 32 PM](https://user-images.githubusercontent.com/100328396/164509620-1d15d494-0183-42d7-9e29-10d1f91b645b.png)

<h4>Special characters</h4>

Because strings must be written within quotes, Java will misunderstand this string, and generate an error:

![Screenshot 2022-04-21 at 10 12 21 PM](https://user-images.githubusercontent.com/100328396/164509786-b8a81a7e-f346-48c8-9195-32a4aa080560.png)

The solution to this problem is to use backslash escape characters.

The backslash (\) escape character turns special characters into string characters:

![Screenshot 2022-04-21 at 10 13 06 PM](https://user-images.githubusercontent.com/100328396/164509904-b2582952-dc4b-41eb-955a-0db7f8bb7209.png)

![Screenshot 2022-04-21 at 10 13 37 PM](https://user-images.githubusercontent.com/100328396/164509988-ddeaf15b-29bf-4ea3-b7da-a1f01cdc67ce.png)


<h4>Math</h4>

The Java Math class has many methods that allows you to perform mathematical tasks on numbers.

<h5>Math.max(x,y)</h5>

The Math.max(x,y) method can be used to find the highest value of x and y:

![Screenshot 2022-04-21 at 10 14 34 PM](https://user-images.githubusercontent.com/100328396/164510134-3ef6d3f7-2413-4248-b039-3ce1b931444c.png)

<h5>Math.min(x,y)</h5>

The Math.min(x,y) method can be used to find the lowest value of x and y:

![Screenshot 2022-04-21 at 10 15 31 PM](https://user-images.githubusercontent.com/100328396/164510271-ab21ceaa-741a-4b92-ace6-f148ae33f803.png)

<h5>Math.sqrt(x)</h5>

The Math.sqrt(x) method returns the square root of x:

![Screenshot 2022-04-21 at 10 16 25 PM](https://user-images.githubusercontent.com/100328396/164510425-ac59435f-2cb1-425e-a869-90bac0259012.png)

<h5>Math.abs(x)</h5>

The Math.abs(x) method returns the absolute (positive) value of x:

![Screenshot 2022-04-21 at 10 17 25 PM](https://user-images.githubusercontent.com/100328396/164510577-f4468770-ea72-4a14-9410-c5b83df33e07.png)

 
<h5>Random Numbers</h5>

Math.random() returns a random number between 0.0 (inclusive), and 1.0 (exclusive):

![Screenshot 2022-04-21 at 10 18 15 PM](https://user-images.githubusercontent.com/100328396/164510707-78a1f140-8a9e-4360-b62f-995f6832a13d.png)

To get more control over the random number, e.g. you only want a random number between 0 and 100, you can use the following formula:


![Screenshot 2022-04-21 at 10 18 59 PM](https://user-images.githubusercontent.com/100328396/164510837-2b6777f8-a98a-437e-ae21-6436bc0f740d.png)

<h4>Java Booleans</h4>

Very often, in programming, you will need a data type that can only have one of two values, like:

* YES / NO
* ON / OFF
* TRUE / FALSE
For this, Java has a boolean data type, which can take the values true or false.

![Screenshot 2022-04-21 at 10 20 23 PM](https://user-images.githubusercontent.com/100328396/164511047-479e6422-67f4-43da-b90d-8eb0a31c3d86.png)

<h4>Boolean Expression</h4>

A Boolean expression is a Java expression that returns a Boolean value: true or false.

You can use a comparison operator, such as the greater than (>) operator to find out if an expression (or a variable) is true:

![Screenshot 2022-04-21 at 10 21 33 PM](https://user-images.githubusercontent.com/100328396/164511211-1e8048a5-dd17-4884-a13d-45f930cf4158.png)





