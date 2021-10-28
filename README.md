import java.util.Scanner;
public class Main
{
	public static void main(String[] args) 
	{
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter your name");
		String name = sc.nextLine();
		System.out.println("Enter your Roll number");
		int roll_no = sc.nextInt();
		System.out.println("Enter your Age");
		int age = sc.nextInt();
		System.out.println("Student Deatails: ");
		System.out.println(name);
		System.out.println(roll_no);
		System.out.println(age);
	}
}
