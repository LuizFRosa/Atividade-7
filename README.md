# Atividade-7

#include <stdio.h>
#include <stdlib.h>

int main() {
	
    // Declaração da variável para armazenar o número
    float c;
    
    printf("Digite o valor de celsius: \n");
    scanf("%f", &c);

    // Verificar o resultado
    float f = c * 1.8 + 32;
	
	printf("A temperatura em Farenheit: %f", f); 
    
    return 0;
}
