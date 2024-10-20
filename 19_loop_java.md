# LOOPS
- We write it once and it should call itself multiple times based on the condition.
- Which reiterate the same thing based on the condition.
- Different types of loops in java:

 `   1. while `

   ` 2. do while`

  `  3. for `

## WHILE LOOP
```JAVA
int i=1;
while(i<5)
{
    System.out.println("Hi " + i);
    i++;
} 
// tab for statement inside curly bracs - indentation
```
O/P:

Hi 1

Hi 2

Hi 3

Hi 4


- i is a iterator here as it iterates (as it's value gets incremented in the loop)
- Concatenation `"Hi" + i`
- When the i becomes 5, the condition will become false and it will jump out of the loop.
```JAVA
int i=1;
while(i<5)
{
    System.out.println("Hi" + i);
    i++;
} 
System.out.println("Bye " + i);
```
O/P:

Hi 1

Hi 2

Hi 3

Hi 4

Bye 5

- When the value of i is 5, it will jump out of the loop. So, now the value of i is 5 as the i is declared outside the loop.
- We can use the `DEBUG` feature in vs code and by using the checkpoint, we can execute the code step by step using step over and can visualize it.

### NESTED LOOP
- Nested while loop
```JAVA
int i=1;
while(i<5)
{
    System.out.println("Hi" + i);
    int j=1;
    while(j<5)
    {
        System.out.println("Bye " + i);
        j++;
    }
    i++;
} 

```
- For every hi, the bye have to be printed for 4 times. So, the same variable will not work.
--------
## DO WHILE LOOP
- There are certain  situation, where you want to execute the block at least once even if the condition is false.

```JAVA
int i=5;
do
{
    System.out.println("Hi " + i);
    i++;
} while(i<5);
```
- When you write while at the start, curly bracs becomes statement. But you write at end, you have to use semicolon.
- It will execute the block atleast once even if the condition is false.
- Exit-controlled loop is the type of the do-while loop in terms of control flow
## FOR LOOP
- In while loop, initialization, condition and increment/decrement is done on three different lines.
- In finite loop, we know when it starts and when it will end.
- There are some loops where we're not sure when it will going to end.

Ex: We are opening the file and printing each character from it. The loop ends when the characters end in the file. And we can't determine when the loop will end.
- While will only check for the condtion.
- In for loop, we can mention three different statements in one line.
```JAVA
for(int i=1;i<5;i++)
{
    System.out.println("Hi" + i);
}
```
- int i=1;i<5;i++ these are three different statements as we're using semicolon after each.
- initial value of i is 1. 
- Computer start their counting from zero because of it's binary format 0 to 1.
```JAVA
for(int i=0;i<4;i++)
{
    System.out.println("Hi" + i);
}
// if we want the loop to print 4 times
```
-  If we start to execute this loop, it takes the i value which is the initial value and check with the condition and execuute the block and the value of i gets incremented.
- Again it checks the value of i and executes the block and the value of i gets incremented.
```JAVA
int j=4;
System.out.println(j+4);
```
O/P: 44
- j(string)+4(int) is cancatenated.
- To resolve this:
```JAVA
int j=4;
System.out.println( (j+4) );
```
O/P: 8

- We can use `for loop` as `while loop`:
```JAVA
int i=0;
for(;i<4;)
{
    System.out.println("Hi" + i);
    i++;
}
//But we have to have two semicolons in it
```

### WHICH LOOP TO USE
- If you know how many iterations you have to go for - `for loop` - in terms of frequency of use
- While reading a file, we don't have a initial value to read each character, at the end of the characters, we have to end the loop - to read file, database - `while loop` - in terms of usage for files, database, network
- Even if the condition is false, but you want to execute atleast once - `do while loop`
