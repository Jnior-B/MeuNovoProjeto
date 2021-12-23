# CODIGO FONTE DESAFIO 1

 

## RESPOSTA

import java.io.IOException;

import java.util.Scanner;

public class DesafBootCamp1 {

	 public static void main(String[] args) throws IOException {
	   Scanner leitor = new Scanner(System.in);
	   System.out.println("Digita o graus ");
	   while (leitor.hasNext()) {
	   double graus = leitor.nextDouble();
	   if (graus <= 360 ) {
	   if(graus ==360 || graus <90) 
			   System.out.println("Bom dia !!");
		   
		   else if (graus ==90 || graus <180) 
			   System.out.println(" Boa tarde!!");
		   else if(graus ==180 ||graus <270) 
			   System.out.println("Boa noite !!");
		   else if(graus ==270 || graus <360) 
			   System.out.println("De Madrugada !!");
		   }
		   else System.out.println("Bom dia ");
	   }
	   }
	   }