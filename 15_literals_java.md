# LITERALS

- Values are called literals because they are literally the values.
```JAVA
int a = 5;
```
- This 5 is called literal.
- We can have any direct values that goes into the range. 
- All these are `decimal` values with base 10.
- If we want to work with `binary` with base 2.
```JAVA
int num = 0b101;
```
O/P: 5
- If we want to work with `hexadecimal`
```JAVA
int num = 0x7E;
```
O/P:126
-  In Java, we can put `underscore` between numbers if we want to differentiate them so it is easy to count if there are many zeros in it.
```JAVA
int num = 10_00_00_000;
```
O/P: 100000000
```JAVA
double num = 12e10;
```
O/P: 1.2E11
- Double will automatically convert assigned int value into double.
```JAVA
char c= 'a';
c++;
```
O/P: b
- We can increment character.
- This is also a literal.

NOTE:
```JAVA
int i=4;
int a= ~i;
System.out.println(a);
```
- ~a is a bitwise NOT of i.
- 00000100 is inverted as 11111011

