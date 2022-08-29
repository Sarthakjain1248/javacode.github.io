# javacode.github.io
import java.util.Scanner;

/*
 * First Java Program
 */
public class HelloSarthak {
      public static void main(String[] args) {
//    	  System.out.println("Hello Sarthak");
//    	  System.out.println("Hello");
//      }
//    	   public static void main(String[] args) {  
    	        //Initialize array  
//    	        int [] arr = new int [] {1, 2, 3, 4, 5};  
//    	        System.out.println("Original array: ");  
//    	        for (int i = 0; i < arr.length; i++) {  
//    	            System.out.print(arr[i] + " ");  
//    	        }  
//    	        System.out.println();  
//    	        System.out.println("Array in reverse order: ");  
    	        //Loop through the array in reverse order  
//    	        for (int i = arr.length-1; i >= 0; i--) {  
//    	            System.out.print(arr[i] + " ");  
//    	        } 
//    	  Scanner sc = new Scanner(System.in);
//    	  String str = sc.nextLine();
//    	  int i = sc.nextInt();
//    	  double d = sc.nextDouble();
//    	  System.out.println(i);
//    	  System.out.println(d);
//    	  System.out.println(str);
//    	  
    	  
//    	  System.out.println("Hello World");
    	        Scanner sc  = new Scanner (System.in);
    	        int B = sc.nextInt();
    	        int H = sc.nextInt();
    	        
    	        if(B >= 0 && H >= 0){
    	        System.out.println(B*H);
    	         } else{ 
    	        System.out.println("java.lang.Exception: Breadth and height must be positive");
    	         }
    	}
    }  
    
