# leap
  import java.util.Scanner;
class Leap{
public static void main(String args[]){
Scanner cc=new Scanner(System.in);
System.out.println(" enter the year");
int n =cc.nextInt();
if(n%400==0){
 if((n%4==0)&&(n%100==0)){
 System.out.println("the year is leap year");
 }
}
 else{
 System.out.println("the given year is not leap year");
 }
 }
 }	
