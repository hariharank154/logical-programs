<h5>Left Aligned Number Pyramid</h5>
<h5>Pattern 1</h5>

```java
public class Func {
    public static void main(String[] args) {
        int n = 5;
        for (int i = 1; i <= n; i++) {  // Loop through each row
            for (int j = 1; j <= i; j++) {  // Print numbers in each row
                System.out.print(i + " "); 
            }
            System.out.println(); // Move to the next line after each row
        }
    }
}
```
`Output`

<pre>
1 
2 2 
3 3 3 
4 4 4 4 
5 5 5 5 5 
</pre>

<h5>Pattern 2</h5>

```java
public class Func {
    public static void main(String[] args) {
        int n = 5;
        for (int i = 1; i <= n; i++) {  // Loop through each row
            for (int j = 1; j <= i; j++) {  // Print numbers in each row
                System.out.print(j + " "); 
            }
            System.out.println(); // Move to the next line after each row
        }
    }
}
```

`Output`

<pre>
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5 
</pre>

<h5>Pattern 3</h5>

```java
public class Func {
    public static void main(String[] args) {
        int n = 5;
        for (int i = n; i >= 1; i--) { // Loop from n to 1 (descending)
            for (int j = 1; j <= i; j++) { // Print i times in each row
                System.out.print(i + " ");
            }
            System.out.println(); // Move to the next line after each row
        }
    }
}
```
`Output`

<pre>
5 5 5 5 5 
4 4 4 4 
3 3 3 
2 2 
1 
</pre>

<h5>Pattern 4</h5>

```java
public class Func {
    public static void main(String[] args) {
        int n = 5;
        for (int i = n; i >= 1; i--) { // Loop from 5 to 1 (descending rows)
            for (int j = 1; j <= i; j++) { // Print increasing numbers in each row
                System.out.print(j + " ");
            }
            System.out.println(); // Move to the next line after each row
        }
    }
}
```
`Output`

<pre>
1 2 3 4 5 
1 2 3 4 
1 2 3 
1 2 
1 
</pre>

<h5>Right Aligned Number Pyramid</h5>
<h5>Pattern 1</h5>

```java
public class Func {

    public static void main(String[] args) {

        int n = 5; // Number of rows

        for (int i = 1; i <= n; i++) { // Loop for each row

            // Print spaces
            for (int j = 1; j <= n - i; j++) {
                System.out.print(" ");
            }

            // Print numbers
            for (int k = 1; k <= i; k++) {
                System.out.print(i);
            }

            // Move to the next line
            System.out.println();
        }
    }
}
```
`Output`

<pre>
        1
      2 2
    3 3 3
  4 4 4 4
5 5 5 5 5
</pre>

<h5>Pattern 2</h5>

```java
public class Func {

    public static void main(String[] args) {

        int n = 5; // Number of rows

        for (int i = 1; i <= n; i++) { // Loop for each row

            // Print spaces
            for (int j = 1; j <= n - i; j++) {
                System.out.print(" ");
            }

            // Print numbers
            for (int k = 1; k <= i; k++) {
                System.out.print(k);
            }

            // Move to the next line
            System.out.println();
        }
    }
}
```
`Output`

<pre>
        1
      1 2
    1 2 3
  1 2 3 4
1 2 3 4 5
</pre>

<h5>Pattern 3</h5>

```java
public class Func {
    public static void main(String[] args) {
        int n = 5; // Number of rows

        for (int i = 1; i <= n; i++) { // Row loop
            for (int j = 1; j < i; j++) { // Print spaces
                System.out.print(" ");
            }

            for (int k = i; k <= n; k++) { // Print numbers
                System.out.print(i);
            }

            System.out.println(); // Move to next line
        }
    }
}
```
`Output`

<pre>
1 1 1 1 1
  2 2 2 2
    3 3 3
      4 4
        5
</pre>

<h5>Pattern 4</h5>

```java
public class Func {
    public static void main(String[] args) {
        int n = 5; // Number of rows

        for (int i = 1; i <= n; i++) { // Row loop
            for (int j = 1; j < i; j++) { // Print spaces
                System.out.print(" ");
            }

            for (int k = i; k <= n; k++) { // Print numbers
                System.out.print(k);
            }

            System.out.println(); // Move to next line
        }
    }
}
```

`Output`

<pre>
1 2 3 4 5
  2 3 4 5
    2 3 4
      3 4
        5
</pre>
  

