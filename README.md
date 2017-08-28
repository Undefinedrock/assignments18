# assignments18
import java.util.Scanner;
public class Exercise1812 {

   
    public static void main(String[] args) {
        Scanner input= new Scanner(System.in);
        System.out.println("Enter a string ：");
        String x=input.next();
        System.out.println("The reserve String is: ");
        reserveDisplay(x);
     
    }
    public static void reserveDisplay(String value){
    reserveDisplay(value,value.length()-1);}
    
    
    public static void reserveDisplay(String value,int high){
    if (high>=0)
    {System.out.print(value.charAt(high));
    reserveDisplay(value,high-1);}
    
            }
}
