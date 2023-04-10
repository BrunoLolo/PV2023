# PV2023
Trabajos
1)
import java.util.*;

public class Main {
    public static void main(String[] args) {
      int n;
      n=2020;
      if(n%100 != 0 && n%4 == 0 || n%400 == 0){
        System.out.println("Año Bisiesto");
      }
      else{
       System.out.println("No es bisiesto");
      }
  }
}

2)
public class MyClass {
    public static void main(String args[]) {
      int x=13;
      switch(x){
          case 1:{
              System.out.println("Enero");
              break;
          }
          case 2:{
              System.out.println("Febrero");
              break;
          }
          case 3:{
              System.out.println("Marzo");
              break;
          }
          case 4:{
              System.out.println("Abril");
              break;
          }
          case 5:{
              System.out.println("Mayo");
              break;
          }
          case 6:{
              System.out.println("Junio");
              break;
          }
          case 7:{
              System.out.println("Julio");
              break;
          }
          case 8:{
              System.out.println("Agosto");
              break;
          }
          case 9:{
              System.out.println("Septiembre");
              break;
          }
          case 10:{
              System.out.println("Octubre");
              break;
          }
          case 11:{
              System.out.println("Noviembre");
              break;
          }
          case 12:{
              System.out.println("Diciembre");
              break;
          }
          default:{
              System.out.println("Incorrecto");
              break;
          }
      
        }
    }
}

3)
import java.util.*;

public class Main {
    public static void main(String[] args) {
      int n, aux;
      n=19;
      aux=1;
      System.out.println("Todos Los Primos Son:");
      for( int j=2; j<=n; j++ ){
        for( int p=2; p<=9 && j%p != 0 || p<=j; p++ ){
          if( j%p == 0 ){
            aux++;
          }
        }
        if( aux == 2 ){
          System.out.println(j);
        }
        aux = 1;
      }
  }
}


4)
import java.util.*;

public class Main {
  public static void main(String[] args){
    int s, i, opcion;
    s = 30;
    i = 8;
    opcion = 1;
    if(s > i){
      switch (opcion){
        case 1:{
          System.out.println("Impares");
          for( int j = i; j<= s; j++ ){
            if( j%2 != 0){
              System.out.println(j);
            }
          }
          break;
        }
        case 2:{
          System.out.print("Pares");
          for( int j = i; j<=s; j++){
            if( j%2 == 0){
              System.out.println(j);
            }
          }
          break;
        }
        default:{
          System.out.print("Erroneo");
          break;
        }
      }
    }
    else{
      System.out.println("Invalido");
    }
  }
}