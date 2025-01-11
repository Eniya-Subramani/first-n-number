# first-n-number
import java.util.Scanner;
Public class PrintNumbers {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.print(&quot;Enter the value of n: &quot;);
int n = sc.nextInt();
System.out.println(&quot;The first &quot; + n + &quot; numbers are:&quot;);
for (int i = 1; i &lt;= n; i++) {
System.out.print(i + &quot; &quot;);
}
}
}
OUTPUT:
Enter the value of n: 5

The first 5 numbers are:
1 2 3 4 5
