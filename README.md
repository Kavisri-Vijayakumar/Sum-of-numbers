
package sumofoddnumber;
public class Sumofoddnumber {
    public static void main(String[] args) {
        int sum=0;
        for(int i=1;i<=100;i++)
        {
            if(i%2!=0){
                sum=sum+i;
            }
            
        }
        System.out.println("the sum: "+sum);
    }
    
}
Output
run:
the sum: 2500
BUILD SUCCESSFUL (total time: 0 seconds)
