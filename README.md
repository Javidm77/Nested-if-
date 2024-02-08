# Nested-if-
Nested If else Example

package com.edubridge5;

import java.util.Scanner;

public class FruitShop1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the Friut name");
		String fn=sc.nextLine();
		System.out.println("Enter the Quantity");
		int qty=sc.nextInt();
		int cost=0;
		
		
		
		if (fn.equals("apple"))
	    {
			if(qty<=20)
		    {
			  cost=qty*5;
			  System.out.println(cost);
		    }
				
	    
	
		   else
		    {
				cost=qty*7;
				System.out.println(cost);
			}
	    }
		
		else if (fn.equals("kiwi"))
		{
			if ((qty>10) && (qty<=25))
			{
				cost=qty*4;
				System.out.println(cost);
			}
			
			else 
			{
				cost=qty*6;
				System.out.println(cost);
			}
		    }
	  
		else if (fn.equals("banana"))
		{
		 if (qty<=100)
		 {
			 cost=qty*3;
				System.out.println(cost);
		 }
		
		else
		{
			cost=qty*4;
			System.out.println(cost);
		}
	}
	System.out.println("");	
	}

}


