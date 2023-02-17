# java
package nothing;
import java.util.Scanner;
public class Sample {

	public static void main(String[] args) {
		Scanner sc= new Scanner(System.in);
		System.out.println("enter number");
		double x=sc.nextDouble();
		if (x>0) {
			System.out.println("It is positive number");
		}
		else if (x==0) {
			System.out.println("It is zero");
		}
		else {
			System.out.println("It is a negative number");
		}
		
	}

}
