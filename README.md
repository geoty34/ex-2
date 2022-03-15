# ex-2
programa
{
	
	funcao inicio()
	{
		inteiro numeros[10]
		
		para(inteiro i=0; i < 10; i++){
			escreva(" Informe um valor: ")
			leia(numeros[i])

		}
		
		limpa()
		
		para(inteiro j=9; j >= 0; j--){
			se(j < 10){
				escreva(numeros[j], ",")
            	}
            	
			se(j == 0){
				escreva(numeros[j])
			}			
		}
	}
}
	
/* $$$ Portugol Studio $$$ 
 * 
 * Esta seção do arquivo guarda informações do Portugol Studio.
 * Você pode apagá-la se estiver utilizando outro editor.
 * 
 * @POSICAO-CURSOR = 89; 
 * @PONTOS-DE-PARADA = ;
 * @SIMBOLOS-INSPECIONADOS = {numeros, 6, 10, 7};
 * @FILTRO-ARVORE-TIPOS-DE-DADO = inteiro, real, logico, cadeia, caracter, vazio;
 * @FILTRO-ARVORE-TIPOS-DE-SIMBOLO = variavel, vetor, matriz, funcao;
 */
