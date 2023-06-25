# lern-java
lerning java

## check version

java -version

```
D:\test\java\test1>java -version
openjdk version "17.0.7" 2023-04-18
OpenJDK Runtime Environment Temurin-17.0.7+7 (build 17.0.7+7)
OpenJDK 64-Bit Server VM Temurin-17.0.7+7 (build 17.0.7+7, mixed mode, sharing)
```

## Main.java

```java
public class Main {

  public static void main(String[] args) {
    int myNum = 15;
    System.out.println(myNum);

    int Num1;
    Num1 = 17;
    System.out.println(Num1);

    int Num2 = 5;
    float myFloatNum = 5.99f;
    char myLetter = 'D';
    boolean myBool = true;
    String myText = "Hello";

    System.out.println("Hello World");
    System.out.println(3 + 3);
    System.out.println(2 * 5);

    String firstName = "John ";
    String lastName = "Doe";
    String fullName = firstName + lastName;
    System.out.println(fullName);
  }
}

```

## compile

```sh
javac Main.java
```

## check file 

```bat
D:\test\java\test1>dir
 Volume in drive D is DATA
 Volume Serial Number is 0CD1-2E18
Directory of D:\test\java\test1
2023-06-10  03:17 PM             1,072 Main.class
2023-06-10  03:17 PM               579 Main.java
               2 File(s)          1,651 bytes
               2 Dir(s)  306,791,075,840 bytes free
```

## check CLASSPATH 

```
D:\test\java\test1>echo %CLASSPATH%
C:\Program Files\Java\jdk-17.0.1\lib
```

## add CLASSPATH

```
set CLASSPATH=C:\Program Files\Java\jdk-17.0.1\lib;D:\test\java\test1\
```

## check CLASSPATH again

```
D:\test\java\test1>echo %CLASSPATH%
C:\Program Files\Java\jdk-17.0.1\lib;D:\test\java\test1\
```

## run 

```
D:\test\java\test1>java Main
15
17
Hello World
6
10
John Doe
```

## run with boset CLASSPATH

```
D:\test\java\test1>java -classpath .:; Main
15
17
Hello World
6
10
John Doe
```

### Windows

```
c:/> echo %CLASSPATH%
```

### Linux/Unix

```
$ echo $CLASSPATH
```

|Function	| Java JAR command|
|--|--|
|Run a JAR file	| jar -jar jarfilename.jar|
|Create a JAR file	| jar cf jarfiletocreate.jar file-list|
|Open a JAR file	| jar xf jar-file-to-open.jar|
|Run a JAR without a manifest	| java -cp jarfilename.jar com.example.MainClass|


## list java map vesion

correct Java version:
```
Java 1.2 uses major version 46
Java 1.3 uses major version 47
Java 1.4 uses major version 48
Java 5 uses major version 49
Java 6 uses major version 50
Java 7 uses major version 51
Java 8 uses major version 52
Java 9 uses major version 53
Java 10 uses major version 54
Java 11 uses major version 55
Java 12 uses major version 56
Java 13 uses major version 57
Java 14 uses major version 58
Java 15 uses major version 59
Java 16 uses major version 60
Java 17 uses major version 61
Java 18 uses major version 62
Java 19 uses major version 63
```



