# 14.ACF-SwitchMult

Also, starting from Java 14, it's possible to supply more than one value (comma-separated) in one arm of the switch statement.

## Listing 14 ACF-SwitchMult/SwitchMult.java Page 35

```java
1.  public class SwitchMult {
2.      public static void main(String[] args) {
3.          String n = "BMW", country = null;
4.          switch (n) {
5.              case "BMW", "Opel", "Audi" -> country = "Germany";
6.              case "Peugeot", "Citroen" -> country = "France";
7.              default -> country = "unknown";
8.          }
9.          System.out.println(n + " -> " + country);
10.     }
11. }
```
