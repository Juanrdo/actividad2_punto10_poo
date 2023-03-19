# actividad2_punto10_poo
package cautroesferas;
import java.util.Scanner;
public class Cautroesferas {

    public static void main(String[] args) {
        double  pesoa,pesob,pesoc,pesod;
        
        Scanner ingresotecl = new Scanner (System.in);
       
        System.out.println("Ingrese el peso de la esfera A: ");
        pesoa = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el peso de la esfera B: ");
        pesob = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el peso de la esfera C: ");
        pesoc = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el peso de la esfera D: ");
        pesod = ingresotecl.nextDouble();
        
        if ((pesoa==pesob)&&(pesoa==pesoc)){
            if (pesod>pesoa){
                System.out.println("la esfera D es la diferente y es mayor");
            }
            else {
                System.out.println("la esfera D es la diferente y es menor");
            }
        }
        else{
            if((pesoa==pesob)&(pesoa==pesod)){
                System.out.println("la esfera C es la diferente");
                if (pesoc>pesoa){
                    System.out.println("y es de mayor peso");
                }
                else{
                    System.out.println("y es de peso menor");
                }
            }
            else {
                if ((pesoa==pesoc)&&(pesoa==pesod)){
                    System.out.println("la esfera B es la diferente");
                if (pesob>pesoa){
                    System.out.println("y es de mayor peso");
                }
                else{
                    System.out.println("y es de peso menor");
                }
                    }
                else {
                    System.out.println("la esfera A es la diferente");
                    if (pesoa>pesob){
                        System.out.println("y es de mayor peso");
                }
                else{
                    System.out.println("y es de peso menor");
                }

    }
    
}
            
        }
    }
}
