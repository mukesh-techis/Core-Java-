# Arrays in java

### Arrays
An array is a collection of similar types of data.The number of values in a Java array is always fixed.     
#### Ex program to create an array

```
class ArrayEx {
    public static void main(String[] args) {
        int ageOfPerson[]=new int[5];//Array creation
        ageOfPerson[0]=12;
        ageOfPerson[1]=20;
        ageOfPerson[2]=5;
        ageOfPerson[3]=24;
        ageOfPerson[4]=46;
        System.out.println(ageOfPerson[0]+"\n");//print one value of an array
        //To print whole Array use for loop
        for(int i=0;i<ageOfPerson.length;i++){
            System.out.println("\n"+ageOfPerson[i]);//Print the whole array
        }
    }
}
```
#### Expected Output
> 12      
> 20          
> 5         
> 24              
> 47              
