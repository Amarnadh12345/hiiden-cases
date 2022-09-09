import java.util.*;
import java.lang.*;
class a{
    public static void main(String args[]){
        int a,b,c,x,s,p;
        Scanner sc = new Scanner(System.in);
        a=sc.nextInt();
        b=sc.nextInt();
        c=sc.nextInt();
        x=Math.abs(a);
        s=Math.abs(b);
        p=Math.abs(c);
        if(x>50 && s>6 && p>100){
            System.out.println(10);
        }
        else if(x>50 && s>60 && p<100){
            System.out.println(9);
        }
        else if(x<50 && s>60 && p>100){
            System.out.println(8);
        }
        else if(x>50 && s<60 && p>100){
            System.out.println(7);
        }
        else if(x>50 || s>60 || p>100){
            System.out.println(6);
        }
        else{
            System.out.println(5);
        }
    }
}
