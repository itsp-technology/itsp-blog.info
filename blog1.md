# Java 8 New Features

Java 8, released in March 2014, introduced several significant enhancements to the Java programming language. Below are some key features:

### 1. Lambda Expressions
Lambda expressions enable functional programming by allowing you to treat functionality as a method argument or return value.

**Example:**
```java
Runnable r = () -> System.out.println("Hello, Lambda!");
new Thread(r).start();