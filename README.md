#include <stdio.h>

int main() {

    char estado[30], estado2[30];
    char cod1[4], cod2[4];
    char cidade[50], cidade2[50];
    int pontos1, pontos2;

    // CARTA 1
    printf("ESTADO: ");
    scanf("%s", estado);

    printf("CIDADE: ");
    scanf("%s", cidade);

    printf("CODIGO: ");
    scanf("%s", cod1);

    printf("PONTOS TURISTICOS: ");
    scanf("%d", &pontos1);

    // CARTA 2
    printf("ESTADO 2: ");
    scanf("%s", estado2);

    printf("CIDADE: ");
    scanf("%s", cidade2);

    printf("CODIGO: ");
    scanf("%s", cod2);

    printf("PONTOS TURISTICOS: ");
    scanf("%d", &pontos2);

    // COMPARAÇÃO
    if (pontos1 > pontos2) {
        printf("CARTA 1 VENCEU!\n");
    } else if (pontos1 < pontos2) {
        printf("CARTA 2 VENCEU!\n");
    } else {
        printf("EMPATE!\n");
    }

    return 0;
}
