# Learning-logic-and-programming
//The first one about helloWorld

public class Arrays {

  public static void main (String[] args) {
  
		/*
		 Module: Learning programming and logic
		 Arrays.
		*/
		
		//Arrays. Concept of declaring variable.
		  /*
    String name_1 = "Albus";
    String name_2 = "Knuth";
		 */
    //Arrays are several values within the "name" variable.
    //In order not to create several variables "name_1", "name_2", etc...
    
   String[] name = new String[2];
   name[0] = "Albus";
   name[1] = "Knuth";
		
  System.out.println ("The ruthless wizard has a name, and he is "+name[0]);
  	
	//The top one is a single, normal array.
	
	//Multidimensional array
	
   String[][] name2 = new String[2][2];
	
   name2[0][0] = "Atomz";
		
   System.out.println ("The patrolman of the blazing flame, he is the "+name2[0][0]);
   
   System.out.println ("The miserable is a master and a player "+name[1]);
  }
}
