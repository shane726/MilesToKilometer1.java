import java.util.Scanner;

public class MilesToKilometer1 {
	public static void main(String[] args) {
	
	
	double miles ;
	
	final double MILES_TO_KILOMETER = 1.609 ;
	
	Scanner newscan = new Scanner(System.in);
	
	System.out.print("Enter miles to be converted : ");
	
	miles = newscan.nextDouble();
	
	System.out.println("Kilometers : " + (miles * MILES_TO_KILOMETER ));
	

	}
}
