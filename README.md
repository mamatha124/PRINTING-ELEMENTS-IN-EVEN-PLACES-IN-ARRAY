# PRINTING-ELEMENTS-IN-EVEN-PLACES-IN-ARRAY
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        int a[];
        a=new int[100];
        Scanner sc= new Scanner(System.in);
        int n=sc.nextInt();// Array length
        for(int i=0;i<n;i++){
            int k=sc.nextInt();
            a[i]=k;
        }
        for(int i=1;i<n;i+=2){
            System.out.print(a[i]+" ");
        }
    }
}
