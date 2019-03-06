# Exercicio19

#include <stdlib.h>
#include <stdio.h>
main ()
{
    system("color 0b");

    int n, soma=0;

    while (n!=0)
    {
        printf("digite um numero: ");
        scanf("%d",&n);

        if (n>=100 && n<=200)
        {
            soma=soma+1;
        }
    }

    printf("Foram digitados entre 100 e 200:\n\n %d numero(s)\n", soma);

    return 0;
}
