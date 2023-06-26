# get start JAVA

## normal HelloWorld

```java
public class HelloWorld { 
    public static void main(String[] args) { 
        System.out.println("Hello, World!");
    }
}
```

## easy short

```java
void main() {
    System.out.println("Hello, World!");
}
```


## or

```java
String greeting() { return "Hello, World!"; }
void main() {
    System.out.println(greeting());
}
```

## compile 

```java
$javac --release 21 --enable-preview Main.java
$java --enable-preview Main
```


