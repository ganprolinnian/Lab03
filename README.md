import java.util.*;

public class JPA03 {
    static Scanner keyboard = new Scanner(System.in);
    
    public static void main(String argv[]) 
        int num;
        int sum = 0;
        
        System.out.println("Input:");
        num = keyboard.nextInt();

        for (int i = 1; i <= num; i++) {
            sum += i;                       
        }
        
        System.out.println("1 + ... + " + num + " = " + sum);
    }
