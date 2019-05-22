# Codigos-em-C--Avaliacao_2
Resolução das questões da segunda avaliação da turma DCA0800.
#include <stdio.h>

int main(){

    int palavra;
    char a;
    palavra = 1;

    printf("Digite uma frase, encerrando-a com ponto final: \n\n");
    scanf("%c", &a);

    while(a != '.'){
        if(a == ' ')
              palavra++;

        scanf("%c", &a);
       }
     printf("\nO periodo eh composto por %d palavras.\n", palavra);

     return 0;
}
