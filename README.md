# dio-desafio-github
Desafio de Projeto - 

[Sujestao de estudo : Java8 Como Programar.]

package dialogo;

import java.util.Scanner;

public class Analisys {

	public static void main(String[] args) {
		
		
		Scanner input = new Scanner(System.in);

		
		int passes = 0;
		int failures = 0;
		int studentCounter = 1;
	
		
		
		while(studentCounter <= 10) {
			
			System.out.print("Enter result (1 = pass ou 2 = fail:) ");
			int result = input.nextInt();
			
			
			if(result == 1) 
				passes = passes + 1;
			
			else 
				failures = failures + 1;
			
			studentCounter = studentCounter + 1;
			
		}
		
		System.out.printf("Passed: %d%n filures: %d%n ", passes, failures);
		
		if(passes > 8) 
			System.out.println("Bonus to sntructor!!");
		
		
		
	}

}
