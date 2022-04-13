//THIS IS A JAVA PROGRAM FOR GENERATING A NUMBER PLATE OF CAR WITH RANDOM THREE LETTERS AND 4 DIGITS.
//HOPE YOU FIND IT USEFUL


public class carplate {
    public static void main(String[] args){

         char a=(char)((int)(Math.random()*26+65));
         char b=(char)((int)(Math.random()*26+65));
         char c=(char)((int)(Math.random()*26+65));
         int x=(int)(Math.random()*9999);

             String s1=""+a+""+b+""+c;
             System.out.println("THE NUMBER PLATE OF CAR IS = ");
             System.out.println(s1+x);
    }
    
}
