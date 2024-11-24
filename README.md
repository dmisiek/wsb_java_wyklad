### Zadanie 4

```java
public class Zadanie4 {
    public static void main(String[] args) {
        System.out.println("Liczby nieparzyste 1-20:");
        int i = 1;
        while (i <= 20) {
            if (i % 2 == 0) {
                i++;
                continue;
            }

            System.out.print(i + " ");
            i++;
        }
    }
}
```

### Zadanie 6
```java
public class Zadanie6 {
    public double firstField;
    public char secondField;

    public Zadanie6(double firstField) {
        this.firstField = firstField;
    }

    public Zadanie6(char secondField) {
        this.secondField = secondField;
    }

    public Zadanie6(double firstField, char secondField) {
        this.firstField = firstField;
        this.secondField = secondField;
    }

    public Zadanie6(char secondField, double firstField) {
        this.secondField = secondField;
        this.firstField = firstField;
    }
}
```

### Zadanie 7
```java
public class Zadanie7 {
    public static final int firstStatic = 1;
    public static final double secondStatic = 1;
}
```

### Zadanie 8
```java
public abstract class First {
    public abstract void f();
}
```

```java
public abstract class Second extends First {
    public abstract void g();
}
```

```java
public class Third extends Second {
    @Override
    public void g() {
        System.out.println("Metoda g()");
    }

    @Override
    public void f() {
        System.out.println("Metoda f()");
    }
}
```
