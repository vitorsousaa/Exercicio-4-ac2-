# Exercicio-4-ac2-
Exercicio 44 ac2 eleições 
import java.util.Scanner;

class exercicioeleicao
{
	public static void main (String[] args)
	{
        Scanner ler = new Scanner(System.in);

        int partido = 0,ptvoto = 0,pdtvoto = 0,plvoto = 0,psdbvoto = 0,nulovoto = 0,brancovoto = 0;
        int i = 0; 
        
           { 
               i++;
               

        System.out.print(" Escolha um partido para votar\n13 = PT\n12 = PDT\n22 = PL\n45 = PSDB\n0 Para anular seu voto\n1 Para votar em branco\n");
	   	partido = ler.nextInt();
       

	    switch(partido)
       
	    {
	    case 13:
	        System.out.print ("Voce escolheu o PT 13\n\n"); 
           
            ptvoto++;
            
	        break;
           
	        System.out.print ("Voce escolheu o PDT 12\n\n");
           
            pdtvoto++;
            
	        break;
            
	    case 22:
	        System.out.print ("Voce escolheu o PL 22\n\n");
            
            plvoto++;
            
	        break;
            
	        System.out.print ("Voce escolheu o PSDB 45\n\n");
            
            psdbvoto++;
            
	        break;
            
	        System.out.print ("Voce votou nulo\n\n");
            
            nulovoto++;
           
	        break;
            
	        System.out.print ("Voce votou em branco\n\n");
            
            brancovoto++;
            
	        break;
            
	       
	    }	 
            } while(i<50);
                    
        System.out.print("\n\n\nTotal dos votos:\n\nPT = "+ptvoto+" votos\nPDT = "+pdtvoto+" votos\nPL = "+plvoto+" votos\nPSDB = "+psdbvoto+" votos\nVotos nulos = "+nulovoto+" votos\nVotos em branco = "+brancovoto+" votos\n");
        
	} 
}    


![image](https://user-images.githubusercontent.com/103973613/169919440-2b4f47df-b90c-439e-a57d-d7ef6a8b0af8.png)
