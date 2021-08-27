//Giovanna Santos Rigolei

//Números Primos


import java.util.*;
class Main {
     public static void main(String[] args) {
     int num, x=1, cot=0, div;
     
      
      Scanner teclado = new Scanner(System.in);
      System.out.println("Informe um número inteiro positivo: ");
      num  = teclado.nextInt();

      if (num == 1 || num == 0){
        System.out.println("O número " + num + " não é um número primo.");
      }


      while (num != 1 && num != 0){
        if (num<0){
          System.out.println("Número negativo inválido, reinicie o programa e imforme um número inteiro positivo.");
          break;
        }
        else{
          while (x <= num){
            div=num % x;
            x=x+1;
            if (div==0){
              cot=cot+1;
            }
          }
          if (cot == 2){
             System.out.println("O número "+num+" é um número primo.");
             break;
          }
          else{
            System.out.println("O número "+num+" não é um número primo.");
            break;
          }
    }
  }
    
 }
}
