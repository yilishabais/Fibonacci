public class Fibonacci {
public static int of(int num){
        if(num==1)
            return 1;
        if(num==2)
            return 1;
        return of(num-1)+of(num-2);
    }
    public static void main(String[] args) {
        // TODO code application logic here
        Fibonacci f=new Fibonacci();
        int i=1;
        while(f.of(i)<200){
            System.out.println("Fobonacci.of("+i+")=="+f.of(i));
            i++;
       }
    }
}
