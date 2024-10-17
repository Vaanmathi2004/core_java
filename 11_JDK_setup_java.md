# JDK SETUP
- IDE stands for Integrated Development Environment.
- Using IDE, we can write a code, compile it, run it, can debug the code and can do everything in IDE.
- Where the code editor used for writing the java code alone.
- IDE's include VS code, eclipse, intelliJ idea, NetBeans
- Among this, VS Code is very light weight and we can do everything in it.
- For compiling the java code, complier is needed. We have to download JDK which stands for Java Development Kit.
- In JDK, we have two versions.
    1. Proprietary key of Oracle
    2. Open source version (there are multiple implementation for open source)
- Java is backward compatible and the basic language features will be same. (there will be minor tweaks, but overall it will be same)
- So even after many updates , the basic language remains same.
- `LTS` stands for Long Term Support. So, there are some versions having LTS even after getting new features frequently.

- In command prompt, 
`>java --version`
- It will give you the version and if it did, jdk is installed.

- `>javac --version`
- It will the java c version for the compiler.
- If it shows the error the javac command is not found, even if you have installed it, that means the path is not set.
- **To verify the path**,
    - Search for environment variables in pc.
    - Click the option of environment variables.
    - You have to make sure that you have a path variable or you can edit anything in system variables(If you want this to be applied to all the systems, different users) - going for system variables
    - The variable name is set as path and set the variable value as your bin folder (c>program files>java>jdk>bin) - copy this from the file explorer path.
    - Once it's done, restart the cmd.