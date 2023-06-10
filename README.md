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
