# Triangle-Project
creates a triangle made of '*' based on user input
package triangleProject;

import java.util.Scanner;
import java.io.*;
import java.lang.*;

public class TriangleProject {

	public static void main(String[] args) {
		System.out.println("Welcome to the triangle maker! Please Enter the size of the triangle");
		Scanner keyboard = new Scanner(System.in);
		int sizeOfTriangle = -(keyboard.nextInt());
		
		
		for(int i = sizeOfTriangle; i < Math.abs(sizeOfTriangle); i++)
		{
		    for(int j = Math.abs(sizeOfTriangle+Math.abs(i)); j > 0; j--)
		    {
		        System.out.print("*");
		    }
		    System.out.println("");
		}

   } 
}
