# m-kemmel
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int n, sum=0;

        System.out.println("Sayı Giriniz: ");
        n= input.nextInt();

        for (int i=n-1; i>=1; i++){
             if(n%i==0){
             sum+=i;
         }
    }
            if(sum==n){
    {
        System.out.println("Mükemmel sayı");
    } else {
        System.out.println("Mükemmel sayı degildir");

    }
}
      
