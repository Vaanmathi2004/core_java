# VARIBLES

- We're trying to solve real world problem with virtual work.
- While replacing it with virtual world solution, we need to work with data.
- We need data as well as processing on it. We may get data from users.
- We store data(processed or not) in database which is a permanent or persistent storage. We can change the data but even if we shutdown the system, the data remains there.
- Database is for permanent storage.
- If we need to store data during processing for temporary purpose, we use variables.
- Let's assume you have a box having data inside it. This box have name too
- The box is variable, data is a value.
- Java is called strongly typed language.
- We can create variables but the variables have to have a type.

- println will print on new line. print will just print on the same line.

```JAVA
class exp
{
    public static void main(String a[])
    {
        int num = 3;
        System.out.println(num);
    }
}
```
- int (type), num(variable name), = (assignment operator) because we're assigning a value, {} is a block

# DATATYPES

- There are two types of data that we work with. One of them is primitive.
- In Java, there are many inbuild variables that we can use and they are primitive datatypes. Primitve means it's simple and easy to work with.
- We can divide primitive into four catagories.
    1. Integer

            1. byte
            2. short
            3. int
            4. long
    2. Float

            1. double
            2. float
    3. Character (Many types)
    4. Boolean (value we can have is true or false)
- This can be further classififed.

### INT

- We have different types in integers because it have different sizes. 
- 1 byte = 8 bits
- Range = 2^7 to 2^7-1 (128 to 127)

|Datatype|Size|Range|
|--|--|--|
|int|4 bytes||
|long|8 bytes||
|short|2 bytes||
|byte|1 byte||

- If we have more bytes, it can occupie more values
- If our value's bits goes beyond 128 bits, we can go for long.

#### BYTE
```JAVA
 byte y=129;
```
- It will show error.

#### LONG
```JAVA
long l = 5854l;
```
- We have put `l` at a end to specify it as long value.

### FLOAT

- Double is by default supported in Java because float is good for limited values and precision. But double can have more values.
- Whenever you're performing scientific calculation, if you want to make it fast and support maximum precision, you can use double.

|Datatype|Size|Range|
|--|--|--|
|float|4 bytes||
|double|8 bytes||

```JAVA
double num = 5.6;
```
- Double variable is created and assigned value.

```JAVA
float num = 5.6;
```
- It will give us error because by default point values are considered as a double.
- So, if we want it to be float value, we have to mention it explicitily.
```JAVA
float num = 5.6f;
```
### CHARACTER

- In other languages, char go for less bits but in java, it goes for 2 bytes.
(In c, it's one byte)
- Java follows `Unicode` not ASCII. (Character not only english but all the characters in the world)
```JAVA
char c = 'hello';
```
- Single quote for character.
- digits within the single quote is also considered as character.
- char variable will only accept the single character.
- Double quotes for string.

### BOOLEAN
- Boolean will only accept true or false.
- There is no subtypes here.
- In other languages, it may represented as 0 1. In Java, we don't do that. Java don't work with 0 and 1.
- Boolean is used for conditions

```JAVA
boolean b = true;
```
- As true itself is keyword, we don't have to use doule quotes.
