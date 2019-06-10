# 01

Realiza un programa que calcule el área de un triángulo

(Area = (base * altura)/2
 
```java
import java.util.Scanner;

public class e01 {
private static Scanner teclado;

	public static void main(String[] args) {
		float base=0, altura=0, area=0;
		teclado = new Scanner(System.in);
		
		System.out.println("Calcular el área de un triángulo");
		//pedir base
		do {
			System.out.print("Base (!=0): ");
			base=teclado.nextFloat();
			teclado.nextLine();
		}while(base==0);

		//pedir altura
		do {
			System.out.print("Altura (!=0): ");
			altura=teclado.nextFloat();
			teclado.nextLine();
		}while(altura==0);
		
		area=(base*altura)/2;
		System.out.println("Area del triángulo: "+area);
	}

}
```
