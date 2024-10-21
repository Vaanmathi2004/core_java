# OBJECT AND CLASS

- JAVA is object oriented programming.
- Every Object have properties and behaviours(methods). (know something and do something)
- If we want to create object, first we need to create class.
- JVM creates object in java.
- The class file we created is compiled into bytecode that goes to JVM and that's where we get the object.

### CREATING A CLASS
- Designing the class:
```JAVA
class Calculator
{
    public int add()
    {
        System.out.println("hi");
        return 0;
    }
}
```
- We have to specify the access to the method.
- Method name `add` with the type of `int`. So it have to return something in the type of int.
- How we call add method in main method:
```JAVA
public class Demo
{
    public static void main(string a[])
    {
        add();
    }
}
```
- error: cannot find symbol add();

symbol : method add()
location: class Demo
1 error
- It says that it cannot find that add method in the location demo.
- So, for the class calculator, we have to create object(instance) which we can use in the class demo.
```JAVA
public class Demo
{
    public static void main(string a[])
    {
        Calculator calc; 
        calc.add();
    }
}
```
- calc is a variable of type calculator. So, we call calc as `reference variable`. Imagine calculator as a type and we're creating reference of it.(int num - num is a primitive variables because int is primitive)
- We created the reference but not created object yet.
- Everytime we create object, space is consumed on the JVM.
```JAVA
public class Demo
{
    public static void main(string a[])
    {
        Calculator calc= new Calculator(); 
        calc.add();
    }
}
```
O/P: hi
- Creating an object of type calculator.
- This is how we create the object.
- calc through which we can access the methods of calculator
- new Calculator() - this is the object of calculator type. We are assigning it to calc which is a calculator type variable.
- We can use this reference variable to call the methods of class calculator.
- new refers to consuming space in JVM. (creating object)
- How much space needed and the variables we have to initialize can be done with calculator.
- As the method add returns the integer, we can accept the value returned using:

```JAVA
class Calculator
{
    public int add()
    {
        System.out.println("hi");
        return 0;
    }
}
public class Demo
{
    public static void main(string a[])
    {
        Calculator calc= new Calculator(); 
        int result = calc.add();
        System.out.println(result);
    }
}
```
O/P: 

hi

0
```JAVA
class Calculator
{
    public int add(a,b)
    {
        int r = a+b;
        return r;
    }
}
public class Demo
{
    public static void main(string a[])
    {
        Calculator calc= new Calculator(); 
        int result = calc.add(4,5);
        System.out.println(result);
    }
}// passing the value
```
O/P:

9