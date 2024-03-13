# D-pattern
I have completed D pattern program  in java
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner Sc = new Scanner(System.in);
	    int n = Sc.nextInt();
	    for(int i=1;i<=n;i++){
	        for(int j=1;j<=n;j++){
	            if(i==1|| j==n || i==n || j==2){
	                System.out.print("*");
	            }
	            else{
	                System.out.print(" ");
	            }
	        }
	       System.out.println();
	    }
	}
}

