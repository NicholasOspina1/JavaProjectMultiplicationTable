# Java Project: Multiplication Table (ISM3254)


-------

# Description <a name="description">

Use loops to produce the multiplication table of 1 to 9 as shown:

<p align="center">
Example: <br/>
<img src="https://i.imgur.com/2nLG8MY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

# My Answer  <a name="scenario">

```ruby
public class Assignment5 { //Nicholas Ospina
  public static void main(String[] args) {
    System.out.println("Multiplication Table\n");
    System.out.print(" ");
    for (int i = 1; i <= 9; i++) {
      System.out.print(" " + i);
    }
    System.out.println("\n----------------------------------");
    for (int i = 1; i <= 9; i++) {
      System.out.print(i + " | ");
      for (int j = 1; j <= 9; j++) {
        System.out.printf("%4d", i * j);
      }
      System.out.println();
    }
  }
}

```
