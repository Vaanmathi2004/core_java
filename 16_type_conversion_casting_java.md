# TYPE CONVERSION AND TYPE CASTING

- Every variable needs a name and a type.
- If you want to change the type of the variable, we can't do that.
```JAVA
byte b=127;
int a=256;
b=a;
 //this will not work (error)
 //trying to narrow down
a=b;
//this will work
// byte value is converted into integer value
// trying to widen up
```
- If we want to want to convert int to byte.
- Implicit conversion of the datatype(automatically) is called `type conversion`.
```JAVA
byte b=127;
int a=25;
//this value will be accomadated in b as well
b=(byte)a;
//to convert the int to byte
```
- Explicitly converting the datatype is called `type casting`.
- Here the int value is within the range of byte value.
- If the int value is not within the range of byte value -- Modulo operation:
```JAVA
byte b=127;
int a=257;
b=(byte)a;
```
- Whenver we assign integer value into byte,it will convert it into modulo which is it will divide the number a which is 257. 257%256 (256 is a range of byte)
- The remainder `1` will be stored in b.

```JAVA
float f=5.6f;
int x=(int)f;
System.out.println(x);
```
O/P: 5
- In this conversion, we'll lose our point values.

# TYPE PROMOTION

```JAVA
byte a=10;
byte b=30;
// result will not be stored in byte variable as it extents the range
int result = a*b;
```
O/P: 300

- The result will not be stored in byte variable as it extents the range.
- In java, the result value will be promoted into integer value and can be stored in integer variable.
- Type promotion refers to the conversion from lower to higher datatype.
___

- Casting concept is important in OOPs.
