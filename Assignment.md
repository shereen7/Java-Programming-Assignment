# Java-Programming-Assignment
Java programming assignment

//Hello guys tok main class, class Assignment
//


     import java.util.Scanner;
        class Assignment{
            public static void main(String[] args){


               Scanner scan = new Scanner(System.in);
               DefKod DefKodObj = new DefKod();  // DefKodObj object to get info from DefKod class

               System.out.println("Enter a string: ");
               String inString = scan.nextLine(); // get input from user variable name = inString based on question if im not mistaken

               DefKodObj.DefKod(inString); //call method
               DefKodObj.checkStringValidity(inString);
               DefKodObj.getStringLen(inString);//call method

        }
    }
