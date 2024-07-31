# Table
print Table 

public class Table {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    System.out.print("Enter a number: ");
    int num = scanner.nextInt();
    System.out.print("Enter the table size (e.g. 10 for 10 rows): ");
    int size = scanner.nextInt();

    System.out.println("Table of " + num + ":");
    for (int i = 1; i <= size; i++) {
      System.out.println(num + " x " + i + " = " + (num * i));
    }
  }
}
