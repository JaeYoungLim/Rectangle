import java.util.Scanner;
public class Rectangle {
	public static void main(String [] args){
		int width, height, perimeter, area;
		Scanner keyboard = new Scanner(System.in);
		
		System.out.println("Enter width of rectangle");
		width = keyboard.nextInt();
		System.out.println("Enter height of rectangle");
		height = keyboard.nextInt();
		
		perimeter = width+width+height+height;
		area = width*height;
		
		System.out.println("The perimeter of the rectanlge is " + perimeter 
				+ ", and the area of the rectangel is " + area);
		
	}

}
