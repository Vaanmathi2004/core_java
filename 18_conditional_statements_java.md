# CONDITIONAL STATEMENTS
- In the execution of program, there are some points where the flow of the program need to be decided (based on the condition). There are many paths at that point.
-  Bunch of statements that will be executed based on some conditions.
- `If else` is used for the execution of statements based on the condition.
`if (x>10)`
- If - keyword, () - within it is condition.
- If is only concerned whether the condition within the bracket returns true or false.
- Java is not dependent on any indentation.
- When if block contains only one statement, curly bracs is not required. 
- When there are blocks of statements, we need to use curly bracs.
- if(), else if(), else

# TERNARY OPERATOR
- Based on conditions, we are assigning a value.
- `?:`
- If the condition is true, it will take the value after the question mark.
- If it's false, it will take value after semicolon and the value will be stored in the variable.
```JAVA
result = n%2==0 ? 10 : 20;
```

# SWITCH STATEMENT
- We can use switch and based on the value, it'll execute the particular case. That's why we say it as switch case statement.
```JAVA
int n=1;
switch(n)
{
    case 1:
        System.out.println("Monday");
    case 2:
        System.out.println("Tuesday");
}
```
- If the n is 1, case 1 block will be executed, but case 2 will also be executed.
- It will not try to match again because it is matched already.
```JAVA
int n=1;
switch(n)
{
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
}
```
- So the special keyword `break` is used. So, if the value is matched and the case block got executed, it will come out of the switch.
```JAVA
int n=3;
switch(n)
{
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    default:
        System.out.println("Enter the valid number");
}
```
- If none of the cases are matching,we can do `default` and  we can print the message.
- The break keyword is avoided on recent updates of java. There is a different syntax used in advanced java.
- Most companies are still using Java 8, where they use break keyword.