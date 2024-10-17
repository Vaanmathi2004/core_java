# HOW JAVA WORKS

- In your machine, you will be having JVM(Java Virtual Machine). 
- Java is platform independent because of JVM.
- Irrespective of OS in your machine, you can run your java application using JVM in any machine, if JVM is installed in your machine.
- JVM itself is platform dependent.
- JVM need to be build for particular OS.
- On top of Hardware, we have OS. On the top of OS, we have JVM.
- JVM will execute java code but JVM will not accept the code directly.
- Java goes multiple steps.
- Java only understands `byte code`. So, we need to convert our code into an unreadable format for the normal human being.
- Java code is converted into byte code using compiler called javac.

`Java code -> javac -> byte code -> JVM -> OS -> Hardware`

- If you're working on the big project, there will be any number of files in it.
- But out of these files, there will be only one file which JVM will execute.
- That first file will depend on other files, execution happens.
- We need to mention that only file and that file need to have main method.
- Out of all the files, the execution starts from this first file.
- That main method have a specific signature. 
`public static void main ( String a[])` - We always need to pass this method.

`Java code -> javac -> byte code -> JVM(look for that particular syntax file) -> OS -> Hardware`

- Java is object oriented. It means everything should be a object and to create object, we need class.

```JAVA
class exp
{
    public static void main(String a[])
    {
        System.out.println("Hello world");
    }
}
```
- The file name and class name are same.
- Once we compile it, the class file is generated `exp.class`. This is our byte code.
- To run the byte code, we need JVM. In terminal, `java exp`.
- If you want to run your java application, you need extra libraries and also need a runtime. For this we need environment.
- Java provides one more layer called JRE (Java Runtime Environment) above the OS.
- JVM is a part of JRE.
- JVM with libraries is a part of JRE.
-  If you want to run your application on any platform, it need to have JRE which will have JVM.
- JDK(JRE(JVM)) - If you want to run your appliation in your machine, you need JDK.
- If your code wants to run in other application, it doesn't needs JDK but need JRE & JVM.
- That's why JAVA is WORa