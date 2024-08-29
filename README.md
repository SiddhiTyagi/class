# class
import java.util.*;
class projectpart1{
    public void main(){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the number of subjects chosen:");
        int size=sc.nextInt();
        String subject[]=new String[size+1];
        /*for(int i=0;i<size;i++){
            subject[i]=sc.nextInt();
        }*/
        for(int i=0;i<size;i++){
        System.out.print("Subjects chosen are "+subject[i]+ ", ");    
        }
    }
}
