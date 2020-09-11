package POO_FAZENDA;

import java.util.Scanner;

public class FAZENDA {

	public static void main(String[] args) {
		// TODO Auto-generated method stub // principal
		
		Scanner ler = new Scanner (System.in);

		ANIMAIS pato =  new ANIMAIS(); 
		

	    System.out.println ("Entre com a idade do pato");
		pato.idade=ler.nextInt();
		System.out.println ("Entre com a altura do pato em centímentros");
		pato.tamanho=ler.nextInt();
		pato.som = "Grasnido";
		pato.voa= false;
		pato.tipo = "Aves";
		pato.descricao = "O animal possui pena e bota ovo";

		pato.emitirsom();
		pato.qualAIdade();
		pato.qualTamanho();
		pato.podeVoar();
		pato.tipoClassificacao();
		pato.descricaoAnimal();
		
		//FIM PATO
		
		
				
		ANIMAIS morcego =  new ANIMAIS(); 
	    System.out.println ("Entre com a idade do morcego");
		morcego.idade=ler.nextInt();
		System.out.println ("Entre com a altura do morcego em centímentros");
		morcego.tamanho=ler.nextInt();
		morcego.som = "Farfalho";
		morcego.voa= true;
		morcego.tipo = "Mamiferos";
		morcego.descricao = "O animal possui pelos e amamenta";
		
		morcego.emitirsom();
		morcego.qualAIdade();
		morcego.qualTamanho();
		morcego.podeVoar();
		morcego.tipoClassificacao();
		morcego.descricaoAnimal();

		//FIM MORCEGO
		
		
		
		
		ANIMAIS vaca =  new ANIMAIS(); 
	    System.out.println ("Entre com a idade da vaca");
	    vaca.idade=ler.nextInt();
		System.out.println ("Entre com a altura da vaca em centímentros");
		vaca.tamanho=ler.nextInt();
		vaca.som = "Mugido";
		vaca.voa= false;
		vaca.tipo = "Mamiferos";
		vaca.descricao = "O animal possui pelos e amamenta";
		
		vaca.emitirsom();
		vaca.qualAIdade();
		vaca.qualTamanho();
		vaca.podeVoar();
		vaca.tipoClassificacao();
		vaca.descricaoAnimal();

		//FIM VACA
		
		
		
		
		ANIMAIS galinha =  new ANIMAIS(); 
	    System.out.println ("Entre com a idade da galinha");
	    galinha.idade=ler.nextInt();
		System.out.println ("Entre com a altura da galinha em centímentros");
		galinha.tamanho=ler.nextInt();
		galinha.som = "Cacarejo";
		galinha.voa= false;
		galinha.tipo = "Aves";
		galinha.descricao = "O animal possui pena e bota ovo";
		
		galinha.emitirsom();
		galinha.qualAIdade();
		galinha.qualTamanho();
		galinha.podeVoar();
		galinha.tipoClassificacao();
		galinha.descricaoAnimal();

		//FIM GALINHA
		
	}
	

}
