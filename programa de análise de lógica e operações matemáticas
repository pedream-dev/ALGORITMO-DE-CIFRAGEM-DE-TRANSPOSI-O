#include <stdio.h>

int main() {
    int n1, n2, n3;

    // Leitura dos dados
    printf("Digite o primeiro numero inteiro: ");
    scanf("%d", &n1);
    printf("Digite o segundo numero inteiro: ");
    scanf("%d", &n2);
    printf("Digite o terceiro numero inteiro: ");
    scanf("%d", &n3);

    // Operações Aritméticas
    printf("\n--- Resultados Aritmeticos ---\n");
    printf("Soma: %d\n", n1 + n2 + n3);
    printf("Subtracao: %d\n", n1 - n2 - n3);
    printf("Multiplicacao: %d\n", n1 * n2 * n3);
    
    // Divisão com verificação de segurança (evitar divisão por zero)
    if (n2 != 0 && n3 != 0) {
        printf("Divisao (n1/n2/n3): %.2f\n", (float)n1 / n2 / n3);
    } else {
        printf("Divisao: Erro (divisao por zero detectada).\n");
    }

    // Operadores Relacionais
    printf("\n--- Comparacoes Relacionais ---\n");
    if (n1 > n2) {
        printf("O primeiro numero (%d) e maior que o segundo (%d).\n", n1, n2);
    } else {
        printf("O primeiro numero (%d) nao e maior que o segundo (%d).\n", n1, n2);
    }
    
    if (n2 < n3) {
        printf("O segundo numero (%d) e menor que o terceiro (%d).\n", n2, n3);
    } else {
        printf("O segundo numero (%d) nao e menor que o terceiro (%d).\n", n2, n3);
    }

    // Operadores Lógicos
    printf("\n--- Validacao Logica ---\n");
    // Verifica se n1 > 0 E n2 é par (resto da divisão por 2 é 0)
    if (n1 > 0 && n2 % 2 == 0) {
        printf("Resultado Logico: Condicao atendida (n1 positivo e n2 par).\n");
    } else {
        printf("Resultado Logico: Condicao nao atendida.\n");
    }

    return 0;
}
