# Java-Programming-Assignment
Java programming assignment
Tok class yang based on UML class diagram dalam soalan.
DefKod class
      
    import java.util.Scanner;
      import java.util.regex.Pattern;

      public class DefKod{

      public void DefKod(String inString){  //method step 1
           System.out.println("The input String is: " + inString);	
      }

      public boolean checkStringValidity(String inString) {
        if(Pattern.matches("[a-z0-9  ]+", inString)) {
            return true;
            }
            return false;
     }
    
     public void getStringLen(String inString){ //method utk step 3
        int stringLen = inString.replace(" ","").length();
        System.out.print("The string length is : " + stringLen);
     }
   
 }
   
 

      


      

