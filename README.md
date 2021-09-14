import java.util.Scanner;
public class Sumofarray
{
public static void main(String[] args)
{

int [] arr = new int [] {1, 2, 3, 4, 5};
int sum = 0;
for (int i = 0; i &lt; arr.length; i++) {
sum = sum + arr[i];
}
System.out.println(&quot;Sum of all the elements of an array: &quot; +
sum);
}
}
