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
#

























