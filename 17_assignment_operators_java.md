# ASSIGNMENT OPERATORS


## ARITHMETIC OPERATORS
|Operators|Operation|
|--|--|
|+|add two numbers|
|-|subtract two numbers|
|*|Multiply two numbers|
|/|quotient of the division of two numbers|
|%|Modulus operator - remainder of the division of two numbers|
|+=|(When performing operation within the same variable) num1 = num1 + 2 becomes num+=2|
|-=||
|*=||
|/=||
|++|Increment  - increment the value by one|
|--|Decrement  - Decrement the value by one|

- num++ - Post increment
- ++num - Pre increment
- The difference between both is when we try to fetch the value. They behave differently.
### Pre increment
```JAVA
int num = 7;
int result= ++num;
```
O/P: 8
- In Pre increment, it will first increment the value itself and fetch the value which is going into the result.
### Post increment
```JAVA
int num = 7;
int result= num++;
```
O/P: 7
- In post increment, first it will fetch the value of num and then increment it.

------
-----

## RELATIONAL OPERATORS
|Operator|Operation|
|--|--|
|<|Less than|
|>|Greater than|
|==|Equal to|
|!=|Not equal to|
|<=|Less than or equal to|
|>|Greater than or equal to|


- All these operators compare two values, and return true or false.
- The output we receive through this operation is boolean value.

## LOGICAL OPERATORS

- If there are many conditions and we need the combined output.
- For this, we can use logical operators.
- It is very important in terms of computation. 
- Computer is smart, it's because of it can decide on multiple conditions.

|Operator|Operation|
|--|--|
|&& (AND)|If both the conditions are true, the output will be true|
|double pipe (OR)|Either one of the conditions is true, the output will be true|
|! (NOT)|Reverse the value|

- Truth table
- AND(&), OR(|). Then why &&, || .
- This is short circuit.
- In OR operation, if the 1st condition is true, it doesn't even check the next condition and provide output as true. Thus it saves time.
- In AND operation, if the 1st condition is false,, it doesn't even check for the 2nd condition and provide output as false.

```JAVA
s =! r
```
- If the r is true, s is assigned with the value as false.

```JAVA
boolean result = a>b || x<y || y<a;
```




