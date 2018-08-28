///////////punto 1////////////////

package punto1;

import java.util.Scanner;

class punto1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int numero,rcuadrado,rcubo;
		
		System.out.println("suministre el numero a operar");
		numero = sc.nextInt();
		
		rcuadrado = numero * numero;
		rcubo = numero * numero * numero;
		
		System.out.println("numero al cuadrado: " + rcuadrado);
		System.out.println("numero al cubo: " + rcubo);
		System.out.println("\n");
		System.out.println("\t\t\tAndres Gaviria - Sebastian Lozano");
	}

}

///////////punto 4////////////////////

package Ejercicios;

import java.util.Scanner;

    public class Ejercicio7 {
    public static void main(String[] args) {
    Scanner sc = new Scanner (System.in);
    int h,a,b,resultado;

    System.out.println("Ingrese lado A del triangulo: ");
    a = sc.nextInt();
    System.out.println("Ingrese lado B del triangulo: ");
    b = sc.nextInt();

    h=a*a+b*b;
    resultado=(int)Math.sqrt(h);
    System.out.println("La hipotenusa del triangulo es: "+resultado);
  }
}

///////////punto 5 //////////////////

package punto5;

import java.util.Scanner;

class punto5 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int num1,num2, suma, resta,producto,division;
		
		System.out.println("suministre el primer numero a operar");
		num1 = sc.nextInt();
		System.out.println("suministre el segundo numero a operar");
		num2 = sc.nextInt();
		
		suma = num1 + num2;
		resta = num1 - num2;
		producto = num1 * num2;
		division = num1 / num2;
		
		System.out.println("el resultado de la suma es: "+suma);
		System.out.println("el resultado de la resta es: "+resta);
		System.out.println("el resultado del producto es: "+producto);
		System.out.println("el resultado de la division es: "+division);
		System.out.println("\n");
		System.out.println("\t\t\tAndres Gaviria - Sebastian Lozano");
	}

}

///////////////punto 7 /////////////////////

package Ejercicios;

    import java.util.Scanner;
    
    public class Ejercicio7 {
    public static void main(String[] args) {
    Scanner sc = new Scanner (System.in);
    int h,a,b,resultado;

    System.out.println("Ingrese lado A del triangulo: ");
    a = sc.nextInt();
    System.out.println("Ingrese lado B del triangulo: ");
    b = sc.nextInt();

    h=a*a+b*b;
    resultado=(int)Math.sqrt(h);
    System.out.println("La hipotenusa del triangulo es: "+resultado);
  }
}
//////////////punto 14 /////////////////////

package punto14;

import java.util.Scanner;

class punto14 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int numero,resultado;
		
		System.out.println("suministre el numero a operar");
		numero = sc.nextInt();
		
		if(numero > 100) {
			resultado = numero + 20;
		}else if(numero == 100) {
			resultado = numero + 1;
		}else {
			resultado = numero - 20;
		}
		
		System.out.println("el resultado es: "+resultado);
		System.out.println("\n");
		System.out.println("\t\t\tAndres Gaviria - Sebastian Lozano");
		
	}

}

//////////////punto 15//////////////////////

package Ejercicios;

import java.util.Scanner;

    public class Ejercicio15 {
    public static void main(String[] args) {
    Scanner sc = new Scanner (System.in);

    int n1, n2, n3;

    System.out.println("Ingrese el valor 1: ");
    n1 = sc.nextInt();
    System.out.println("Ingrese el valor 2: ");
    n2 = sc.nextInt();
    System.out.println("Ingrese el valor 3: ");
    n3 = sc.nextInt();
    // Mayores
    if(n1>n2 && n1>n3) {
    System.out.println("El numero mayor es: "+n1);
    }
    if(n2>n1 && n2>n3) {
    System.out.println("El numero mayor es: "+n2);
    }
    if(n3>n1 && n3>n2) {
    System.out.println("El numero mayor es: "+n3);
    }
      // Menores
    if(n1<n2 && n1<n3) {
    System.out.println("El numero menor es: "+n1);
    }
    if(n2<n1 && n2<n3) {
    System.out.println("El numero menor es: "+n2);
    }
    if(n3<n1 && n3<n2) {
    System.out.println("El numero menor es: "+n3);
    }
  }
}
