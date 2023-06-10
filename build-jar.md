To build a JAR (Java Archive) file from your Java code, you can follow these steps:

Step 1: Create a file named `Main.java` and paste your code inside it.

Step 2: Open a terminal or command prompt and navigate to the directory where you have saved the `Main.java` file.

Step 3: Compile the Java code by running the following command:
```
javac Main.java
```
This will generate a compiled bytecode file named `Main.class`.

Step 4: Create a manifest file named `Manifest.txt` and add the following line to it:
```
Main-Class: Main
```
Note that there should be a blank line after the `Main-Class` line.

Step 5: Create the JAR file by running the following command:
```
jar cfm MyJar.jar Manifest.txt Main.class
```
This command creates a JAR file named `MyJar.jar` with the compiled `Main.class` file and includes the `Manifest.txt` file.

Step 6: You now have your JAR file `MyJar.jar`, which can be executed using the `java -jar` command:
```
java -jar MyJar.jar
```
This will run your Java program contained within the JAR file.

Note: Make sure you have the Java Development Kit (JDK) installed and the `javac` and `jar` commands are available in your system's PATH.

That's it! You have successfully built a JAR file from your Java code.
