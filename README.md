- 👋 Hi, I’m @DiegoAntonioCordovaMisaico
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
DiegoAntonioCordovaMisaico/DiegoAntonioCordovaMisaico is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
//CORDOVA MISIACO DIEGO ANTONIO
//EJERCICIO_01_ALGORITMOS
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_01_al;

/**
 *
 * @author USUARIO
 */
public class Ejercicio_01_AL {

    public static void main(String[] args) {
        System.out.println("UNIVERSIDAD PERUANA LOS ANDES");
    }
}




//EJERCICIO_02_ALGORITMOS
//CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_02_al;

/**
 *
 * @author USUARIO
 */
public class Ejercicio_02_AL {

    public static void main(String[] args) {
        System.out.println("DIEGO ANTONIO CORDOVA MISAICO");
    }
}



//CORDOVA MISAICO DIEGO ANTONIO
//EJERCICIO_03_ALGORITMOS
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_03_al;

import java.io.IOException;
import static java.lang.System.in;

/**
 *
 * @author USUARIO
 */
public class Ejercicio_03_AL {

     public static void main(String[] args) throws IOException {
        try (in) {
            int i, suma;
            suma = 0;
            for (i=1; i<=5; i++) {
                System.out.print("PROCESO " + i);
                suma=suma+i;
                System.out.println();
            }   System.out.println("Valor de suma: " + suma);
        }
    }

}




//AREA Y PERIMETRO DE UN CUADRADO
//CORDOVA MIASICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.ejercico_04_al;

import java.util.Scanner;

/**
 *
 * @author USUARIO
 */
//AREA Y PERIMETRO DE UN CUADRADO
public class Ejercicio_04_PT {
public static void main(String[] args){
 Scanner entrada=new Scanner (System.in) ;
double lado;
double area;
double per;
System.out.println("escribe el lado del cuadrado:");
lado=entrada.nextDouble();
area=lado*lado;
per=(lado+lado+lado+lado);
System.out.println("el area del cuadrado es: "+area);
System.out.println("El perimetro del cuadrado es:"+per);
}
}





//CORDOVA MISAICO DIEGO ANTONIO
//AREA Y PERIMETRO DE UN ROMBOIDE
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.ejercico_04_ro;

import java.util.Scanner;

/**
 *
 * @author USUARIO
 */
//AREA Y PERIMETRO DE UN ROMBOIDE
public class Ejercicio_04_RO {
 private static Scanner sc;
 
  public static void main(String[] args){
          
        double perimetro, area;
        double base = leerNumeroReal("Introduce la base del romboide: ");
        double altura = leerNumeroReal("Introduce la altura del romboide: ");
        perimetro = 2 * (base+altura);
        area = base * altura;
  
        System.out.printf("%nEl perímetro del romboide de base %.2f y altura %.2f es %.2f.", base, altura, perimetro);
        System.out.printf("%nEl área del romboide de base %.2f y altura %.2f es %.2f.", base, altura, area);
    }
  
    private static double leerNumeroReal(String s){
        sc = new Scanner(System.in);
        System.out.print(s);
        return sc.nextDouble();
    }
}





//CORDOVA MISAICO DIEGO ANTONIO
//AREA Y PERIMETRO DE UN RECTANGULO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.ejercico_04_ra;

import java.util.Scanner;

/**
 *
 * @author USUARIO
 */
//AREA Y PERIMETRO DE UN RECTANGULO
public class Ejercicio_04_RA {
 private static Scanner sc;
 
  public static void main(String[] args){
          
        double perimetro, area;
        double base = leerNumeroReal("Introduce la base del rectangulo: ");
        double altura = leerNumeroReal("Introduce la altura del ractangulo: ");
        perimetro = 2 * (base+altura);
        area = base * altura;
  
        System.out.printf("%nEl perímetro del rectángulo de base %.2f y altura %.2f es %.2f.", base, altura, perimetro);
        System.out.printf("%nEl área del rectángulo de base %.2f y altura %.2f es %.2f.", base, altura, area);
    }
  
    private static double leerNumeroReal(String s){
        sc = new Scanner(System.in);
        System.out.print(s);
        return sc.nextDouble();
    }
}




//CORDOVA MISAICO DIEGO ANTONIO
//AREA Y PERIMETRO DE UN TRIANGULO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercico_04_al;

import java.util.Scanner;

/**
 *
 * @author USUARIO
 */
//AREA Y PERIMETRO DE UN TRIANGULO
//CORDOVAMISAICO DIEGO ANTONIO
public class Ejercico_04_AL {

   public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    double lado1, lado2, lado3, area,sp, perimetro;
    System.out.println("ingresa el primer lado del triangulo:");
    lado1 = sc.nextDouble();
    System.out.println("ingresa el segundo lado del triangulo:");
    lado2 = sc.nextDouble();
    System.out.println("ingresa el tercer lado del triangulo:");
    lado3 = sc.nextDouble();

    perimetro = lado1 + lado2 + lado3;
    sp = (lado1 + lado2 + lado3)/2;
    area = (Math.sqrt(sp*(sp-lado1) * (sp-lado2) * (sp-lado3)));

    System.out.println("EL area del triangulo es de: "+ area);
    System.out.println("Y el su perimetro es de: "+ perimetro);
  }
}




//CORDOVA MISAICO DIEGO ANTONIO
//AREA Y PERIMETRO DE UN TRAPECIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.ejercico_04_al;

import java.util.Scanner;

/**
 *
 * @author USUARIO
 */
//CORDOVA MISAICO DIEGO ANTONIO
//AREA Y PERIMETRO DE UN TRAPECIO
public class Ejercicio_04_TA {
public static void main(String[] args) {
        Scanner ingreso=new Scanner(System.in);  
        double P, A, B, Bb, h, l1, l2, l3, l4;
        System.out.print("23. TRAPECIO - Mostrar el área y perímetro.\n\n");        
        System.out.print("INGRESE BASE MAYOR   : ");
        B = Double.parseDouble(ingreso.next());
        System.out.print("INGRESE BASE MENOR   : ");
        Bb = Double.parseDouble(ingreso.next());
        System.out.print("INGRESE ALTURA       : ");
        h = Double.parseDouble(ingreso.next());        
        A = ((B * Bb) * h) / 2;
        System.out.println("ÁREA                 : " + A + " cm.");
        System.out.println("");  
        System.out.print("INGRESE LADO 01      : ");
        l1 = Double.parseDouble(ingreso.next());
        System.out.print("INGRESE LADO 02      : ");
        l2 = Double.parseDouble(ingreso.next());
        System.out.print("INGRESE LADO 03      : ");
        l3 = Double.parseDouble(ingreso.next());
        System.out.print("INGRESE LADO 04      : ");
        l4 = Double.parseDouble(ingreso.next());
        P = l1 + l2 + l3 + l4;
        System.out.println("PERÍMETRO            : " + P + " cm.");
    }     
}





//CORDOVA MISAICO DIEGO ANTONIO
//AREA Y PERIMETRO DE UN ROMBO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package com.mycompany.ejercico_04_al;

import java.util.Scanner;

/**
 *
 * @author USUARIO
 */
//AREA Y PERIMETRO DE UN ROMBO
public class Ejercicio_04_RP {
    public static void main(String[] args) {
        Scanner ingreso=new Scanner(System.in);  
        double D, dd, A, L, P;        
        System.out.print("INGRESE DIAMETRO MAYOR : ");
        D = Double.parseDouble(ingreso.next());
        System.out.print("INGRESE DIAMETRO MENOR : ");
        dd = Double.parseDouble(ingreso.next());                        
        A = (D * dd)/2;
        System.out.println("ÁREA                   : " + A);
        System.out.println("");
        System.out.print("INGRESE LADO           : ");
        L = Double.parseDouble(ingreso.next());
        P = 4 * L;
        System.out.println("PERÍMETRO              : " + P);                
    }      
}



 * //calcule el promedio de 5 notas ingresadas por teclado.
 * //CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_05_al;

import java.util.Scanner;

/**
 *
 * @author USUARIO
 * //calcule el promedio de 5 notas ingresadas por teclado.
 * //CORDOVA MISAICO DIEGO ANTONIO
 */
public class Ejercicio_05_AL {

    public static void main(String[] args) {
        try (Scanner scanner = new Scanner(System.in)) {
            System.out.println("ingrese la primera nota: ");
            double nota1= scanner.nextDouble();
            System.out.println("ingrese la segunda nota: ");
            double nota2= scanner.nextDouble();
            System.out.println("ingrese la tercera nota: ");
            double nota3= scanner.nextDouble();
            System.out.println("ingrese la cuarta nota: ");
            double nota4= scanner.nextDouble();
            System.out.println("ingrese la quinta nota: ");
            double nota5= scanner.nextDouble();
            
            double resultado = (nota1+nota2+nota3+nota4+nota5)/5;
            
            System.out.println("el promedio de notas es "+resultado);
        }
    }
}




//calcule la multiplicación de 5 números ingresados por teclado.
    //CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_06_al;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

/**
 *
 * @author USUARIO
 * //calcule la multiplicación de 5 números ingresados por teclado.
    //CORDOVA MISAICO DIEGO ANTONIO
 */
public class Ejercicio_06_AL {

    public static void main(String args[]) throws IOException {
        BufferedReader bufEntrada = new BufferedReader(new InputStreamReader(System.in));
        int mul;
        int n1;
        int n2;
        int n3;
        int n4;
        int n5;
        System.out.println("Ingrese el primer numero: ");
        n1 = Integer.parseInt(bufEntrada.readLine());
        System.out.println("Ingrese el segundo numero:");
        n2 = Integer.parseInt(bufEntrada.readLine());
        System.out.println("Ingrese el tercer numero:");
        n3 = Integer.parseInt(bufEntrada.readLine());
        System.out.println("Ingrese el cuarto numero:");
        n4 = Integer.parseInt(bufEntrada.readLine());
        System.out.println("Ingrese el quinto numero:");
        n5 = Integer.parseInt(bufEntrada.readLine());
        mul = n1*n2*n3*n4*n5;
        System.out.println("La multiplicacion es: "+mul);
}


}





//calcular la multiplicación entre la suma de los primeros 5 números y la suma de los 5 últimos numeros
    //CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */
package com.mycompany.ejercicio_07_al;
import java.util.Scanner;

/**
 *
 * @author USUARIO
 * //calcular la multiplicación entre la suma de los primeros 5 números y la suma de los 5 últimos numeros
    //CORDOVA MISAICO DIEGO ANTONIO
 */
public class Ejercicio_07_AL {

public static void main(String[] args) {
        Scanner scanner= new Scanner(System.in);
        System.out.println("Ingrese número 1:");
        double n1= scanner.nextDouble();
        System.out.println("Ingrese número 2:");
        double n2= scanner.nextDouble();
        System.out.println("Ingrese número 3:");
        double n3= scanner.nextDouble();
        System.out.println("Ingrese número 4:");
        double n4= scanner.nextDouble();
        System.out.println("Ingrese número 5:");
        double n5= scanner.nextDouble();
        System.out.println("Ingrese número 6:");
        double n6= scanner.nextDouble();
        System.out.println("Ingrese número 7:");
        double n7= scanner.nextDouble();
        System.out.println("Ingrese número 8:");
        double n8= scanner.nextDouble();
        System.out.println("Ingrese número 9:");
        double n9= scanner.nextDouble();
        System.out.println("Ingrese número 10:");
        double n10= scanner.nextDouble();
        
        double r1 = (n1+n2+n3+n4+n5);
        double r2 =(n6+n7+n8+n9+n10);
        
        double r3 =(r1*r2);  
        
        System.out.println("suma de los 5 primeros numeros "+r1);
        System.out.println("suma de los 5 ultimos números "+r2);
        System.out.println("multiplicasion "+r3);
    }
}





//AREA DE UN CIRCULO
 * //CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_08_al;
import java.util.Scanner;

/**
 *
 * @author USUARIO
 * //AREA DE UN CIRCULO
 * //CORDOVA MISAICO DIEGO ANTONIO
 */
public class Ejercicio_08_AL {

    public static void main (String[] args) {
        Scanner entrada = new Scanner(System.in);
        double pi = 3.14159265;
        int r = 5;
        System.out.println("Calcular el area de un circulo");
        double area = pi * r * r;
        System.out.println("El area del circulo es : " + area);
    }
}









 * //SUMA DE LAS AREAS DE UN CIRCULO
   //CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_09_al;

import java.util.Scanner;


/**
 *
 * @author USUARIO
 * //SUMA DE LAS AREAS DE UN CIRCULO
   //CORDOVA MISAICO DIEGO ANTONIO
 */
public class Ejercicio_09_AL {
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        double pi = 3.14159265;
        double r1 = 8.9;
        double r2= 6.7;
        double r3= 7.9;
        System.out.println("SUMA DE LAS 3 AREAS 8.9+6.7+7.9 ");
 double are = (pi * r1 * r1) + (pi * r2 *r2) + (pi * r3 *r3);    
        System.out.append("La suma de las 3 areas es: " + are);
    }
}







 //SUMA DE LAS 8 AREAS DE UN CIRCULO
   //CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_10_al;

import java.util.Scanner;



/**
 *
 * @author USUARIO
 * //SUMA DE LAS 8 AREAS DE UN CIRCULO
   //CORDOVA MISAICO DIEGO ANTONIO
 */
public class Ejercicio_10_AL {
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        double pi = 3.14159265;
        double r1 = 18.9;
        double r2= 16.7;
        double r3= 71.9;
        double r4= 4.6;
        double r5= 6.7;
        double r6=5.6;
        double r7=4.7;
        double r8=10;
        System.out.println("Calcular la suma de las 8 areas 18.9+16.7+71.9+4.6+6.7+5.6+4+7+10");
        double are = (pi * r1 * r1) + (pi * r2 *r2) + (pi * r3 *r3) + (pi * r4 * r4) + (pi * r5 *r5)+ (pi * r6 * r6) + (pi * r7 * r7) + (pi * r8 * r8);       
        System.out.println("La suma de las 8 areas de los circulos es: " + are);
    }
}




* //ingresar un número favorito por teclado y luego el computador debe mostrar el mensaje “Tu numero favorito es numero ingresado”.
  //CORDOVA MISAICO DIEGO ANTONIO
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Project/Maven2/JavaApp/src/main/java/${packagePath}/${mainClassName}.java to edit this template
 */

package com.mycompany.ejercicio_11_al;

import java.util.Scanner;



/**
 *
 * @author USUARIO
 * //ingresar un número favorito por teclado y luego el computador debe mostrar el mensaje “Tu numero favorito es numero ingresado”.
  //CORDOVA MISAICO DIEGO ANTONIO
 */
public class Ejercicio_11_AL {
  public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        int num;
        System.out.println("MOSTRAR TU  NUMERO FAVORITO ");
        System.out.println("INGRESA TU NUMERO FAVORITO : ");
        num = entrada.nextInt();
        System.out.println("TU NUMERO FAVORITO ES: "+num);
    }
}
