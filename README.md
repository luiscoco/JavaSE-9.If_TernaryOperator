# JavaSE-9.If_TernaryOperator

In Java, the if statement is used for conditional branching, and the ternary operator (? :) provides a concise way to express a simple conditional operation. Let me show you examples of both.

## 1. if statement

```java
public class IfExample {
    public static void main(String[] args) {
        int number = 10;

        if (number > 0) {
            System.out.println("The number is positive.");
        } else {
            System.out.println("The number is non-positive.");
        }
    }
}
```

In this example, if the number is greater than 0, it prints "The number is positive." Otherwise, it prints "The number is non-positive."

## 2. Ternary Operator (? :):

The same logic can be expressed more concisely using the ternary operator:

```java
public class TernaryOperatorExample {
    public static void main(String[] args) {
        int number = 10;

        String result = (number > 0) ? "The number is positive." : "The number is non-positive.";

        System.out.println(result);
    }
}
```

Here, the ternary operator checks if number > 0. If true, it assigns "The number is positive." to the variable result; otherwise, it assigns "The number is non-positive." The result is then printed.

The ternary operator has the following syntax:

```java
variable = (condition) ? expressionIfTrue : expressionIfFalse;
```

It's a compact way of writing a simple if-else statement.
