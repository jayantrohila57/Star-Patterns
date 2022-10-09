# Star Patterns

## Code Template For JAVA
```
public class Main {
    static void Pattern(int n) {
       // ------ADD YOUR PATTERN HERE-----
    }
    public static void main(String[] args) {
        Pattern(5); //-------LINES OF THE PATTERN------
        }
}
```

## Square

```
int n=5;
for (int i = 1; i <= n; i++) {
    for (int j = 1; j <= n; j++) {
        System.out.print("* ");
    }
    System.out.println();
}
```

### Solution

```
* * * * *
* * * * *
* * * * *
* * * * *
* * * * *
```

## Increasing Triangle

```
int n=5;
for (int i = 1; i <= n; i++) {
    for (int j = 1; j <= i; j++) {
        System.out.print("* ");
    }
    System.out.println();
}
```

### Solution

```
*
* *
* * *
* * * *
* * * * *
```

## Decreasing Triangle

```
int n=5;
for (int i = 1; i <= n; i++) {
    for (int j = i; j <= n; j++) {
        System.out.print("* ");
    }
    System.out.println();
}
```

### Solution

```
* * * * *
* * * *
* * *
* *
*
```
