# algorithm

import java.util.Scanner;

public class Main {
    
    public static void main(String[] args){
        
        Scanner scan = new Scanner(Systemin);
        
        int a = scan.nextInt();
        int b = scan.nextInt();
        int v = scan.nextInt();
        
        int result = (v-b) / (a-b);
        int remainder = (v-b) % (a-b);
        
        if ( remainder != 0){
            result++;
        }
        
        System.out.println(result);
        
    }
    
}
