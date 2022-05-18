# Java-Programming-Assignment
Java programming assignment
Tok class yang based on UML class diagram dalam soalan.
DefKod class
      
    public class DefKod{

          public void DefKod(String inString){  //method step 1
               System.out.println("The input String is: " + inString);
          }


          public void getStringLen(String inString){ //method utk step 3
        
              int stringLen = inString.replace(" ","").length();
              System.out.print("The string length is : " + stringLen);
    
          }
          public void checkStringValidity(String inString){
        boolean flag = true;
        for (int i = 0; i < inString.length(); i++) {
           char ch = inString.charAt(i);
           if (!(ch >= 'a' && ch <= 'z'|| ch >= '0' && ch <= '9')) {
              flag = false;
            DefKod(inString);
           }
        }
        if(flag)
           System.out.println("The input string is: " + inString);
        else
           System.out.println("Your input is incorrect!");
        
     }
    }   
