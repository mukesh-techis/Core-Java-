# Arrays in java

### Arrays
An array is a collection of similar types of data.The number of values in a Java array is always fixed.     
#### Ex program to create an array

```
class ArrayEx {
    public static void main(String[] args) {
        int ageOfPerson[]=new int[5];
        ageOfPerson[0]=12;
        ageOfPerson[1]=20;
        ageOfPerson[2]=5;
        ageOfPerson[3]=24;
        ageOfPerson[4]=47;
        System.out.println(ageOfPerson[0]);
        System.out.println(ageOfPerson[1]);
        System.out.println(ageOfPerson[2]);
        System.out.println(ageOfPerson[3]);
        System.out.println(ageOfPerson[4]);
    }
}
```
#### Expected Output
> 12      
> 20          
> 5         
> 24              
> 47              
