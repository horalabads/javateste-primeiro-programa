# javateste-primeiro-programa
package primeiropacote;

public class primeiroprograma {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.out.println("Olá mundo"); 
		String nome = "João V";
		System.out.println("Olá, " + nome);
		
		 int idade = 19;
		 System.out.println("Idade:" + idade);
		 double altura = 1.86;
		 float peso = 98.5f;
		 System.out.println("Altura:" + altura);
		 // + - * / %
		 int valor1 = 7;
		 int valor2 = 3;
		 System.out.println(valor1 + valor2); // 10
		 System.out.println(valor1 - valor2); // 4
		 System.out.println(valor1 * valor2); // 21
		 System.out.println(valor1 / valor2); // 2.33333
		 System.out.println(valor1 % valor2); // 1
		 
		 boolean par = true;
		 boolean ímpar = false;
		 
		 int valor;
		 valor = 2;
		 
		 if(valor % 2 == 0) {
			par = true;
			System.out.println("par");
		 }else {
		   ímpar = true;
		   System.out.println("ímpar");
		 }
		 
		 
		 }
		 
	}


