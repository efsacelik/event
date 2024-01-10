# event
It suggests events according to weather. 
package patikaAcademy;

import java.util.Scanner;

public class etkinlikOnerme {

	public static void main(String[] args) {
		

		Scanner scanner= new Scanner(System.in);
		 System.out.println("Enter the heat");
		int heat = scanner.nextInt();
		
		if (heat<5 ) {
			System.out.println("You can go skiing");
		}  else if (5<=heat && heat<25) {
			  if ( 5<=heat && heat<15 ){
			  System.out.println("You can go to cinema");
			  } else if ( 15<=heat && heat<25 ){
			  System.out.println("You can go to picnic");
			  }
			
			}
			  else {
					System.out.println("You can go to swimming");
			}
		}
			
			
			
			
			
	}
