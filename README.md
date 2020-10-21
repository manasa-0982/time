# time

Code:

package time;
import java.util.*;
public class Time {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int min=sc.nextInt();
        int day=min/1440;
        int years=day/365;
        int  days=day%365;
        System.out.println("years:" +years);
        System.out.println("days:" +days);
    
        
    }
    
}
