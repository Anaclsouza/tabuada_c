# tabuada_c

#include<stdio.h>
#include<locale.h>
#include<math.h>
 
      int main (){   
    
    
      setlocale(LC_ALL, "portuguese"); 
    
     int num,c=0; 
     
      printf("\n Digite um número inteiro para calcular sua tabuada! \n");
      scanf("%d",&num);
    
      for(c=0;c<=10;c++)
      {
    	printf("%d x %d= %d \n",num,c,num*c);
	  }   
      }
