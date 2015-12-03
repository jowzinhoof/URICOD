#include <stdio.h>
  
int main() {
  
    int x, s, g=0, a=0, d=0;
     
    do{
              
       scanf("%d", &s);      
             
       if (s==1){
       a++;
       }
       else if(s==2)
       {
       g++;
       }
       else if(s==3)
       {
       d++;
       }
       }while(s!=4);
 
       printf("MUITO OBRIGADO\n");
       printf("Alcool: %d\n", a);
       printf("Gasolina: %d\n", g);
       printf("Diesel: %d\n", d);
                                      
    system("pause>>null");
}
