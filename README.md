# Assignment3
package Session7_Assignment;

import java.util.Scanner;

public class SubstringOfStringWithoutInbuilt {
	
	public static void main(String[] args) {
		
		String str1, sub1;
	     Scanner scan = new Scanner(System.in);
	      System.out.println("Enter the main string");
	       str1 = scan.next();
	       char[] strarr= str1.toCharArray();
	       System.out.println("Enter the sub string");
	       Scanner scan1 = new Scanner(System.in);
	       sub1 = scan1.next();
	     char[] subarr = sub1.toCharArray();
	       System.out.println(" the string is:"+(isPresent(subarr,strarr)));
	}

	private static boolean isPresent(char[] subarr, char[] strarr) {
		// TODO Auto-generated method stub
	
		return true;
	}
	
}
