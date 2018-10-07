# compailer-lab
package thff;

import java.util.Scanner;

public class Good {
    public static void main(String[] args){
    	
    String[] keyword={"int","float","if"};
     String[] value = {"5","6","2"};
     String[] operator={"+","-","="};
     String[] logical={"<=",">=",">","<","=="};
     String[] other={""};
     int f=0;
     
     
     Scanner sc=new Scanner(System.in);
    String input = sc.nextLine();
    
    
     for(int k=0;k<keyword.length;k++)
  {
         if(input==keyword[k])
             f=1;
         {
             System.out.println("found at "+k+"postion");
             
         }
       
     }
     for(int k=0;k<value.length;k++)
     {
         if(input==value[k])
             f=1;
         {
         System.out.println("found"+k+"positon");
         }
     }
     for(int k=0;k<operator.length;k++)
     {
       if(input==operator[k]) 
           f=1;
       { 
           
           System.out.println("found"+k+"position");
       }
       
     }
     
         for(int k=0;k<logical.length;k++){ 
             
               if(input==logical[k]) 
               f=1;
                       { 
           
           System.out.println("found"+k+"position");
       }
         }
         if(f==0){
           for(int k=0;k<other.length;k++)
         {
         System.out.println("found at"+k +"position");
         }
         
           
         }
 
 
 
 
}
}
