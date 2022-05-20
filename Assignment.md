# Java-Programming-Assignment
Java programming assignment

//Hello guys tok main class, class Assignment
//


     import java.util.Scanner;
     import java.util.regex.Pattern;
     public class Assignment{
       private static String inString;
          private static int stringLen;


       public static void main(String[] args){
        boolean repeat = true;
           DefKod DefKodObj = new DefKod();

         //To loop until the user enters the correct input
        while(repeat) {
          Scanner sc = new Scanner(System.in);
          System.out.println("Enter the input string : ");
          //DefKod = new DefKod();
          String inString = sc.nextLine();
            if(DefKodObj.checkStringValidity(inString)) {
                  DefKodObj.DefKod(inString);
                  DefKodObj.getStringLen(inString);
                 repeat = false;
              }
          else {
           System.out.println("Invalid Input");
           }
        }
    
    }
    }
