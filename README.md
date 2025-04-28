#include <stdio.h>

int main() {

    char estado[30], estado2[30];
    char codigocarta[4], codigocartas02[4];
    char cidade[50], cidade02[50];
    int pontosturisticos, pontosturisticos02;
    float populacao, populacao02; 
    float pib, pib02;
    float area, area02;
    
    // DADOS DA PRIMEIRA CARTA //

    printf("ESTADO: ");
    scanf("%s", estado);

    printf("CIDADE: ");
    scanf("%s", cidade);

    printf("CODIGO DE CARTAS: ");
    scanf("%s", codigocarta);

    printf("PONTOS TURISTICOS: ");
    scanf("%d", &pontosturisticos);

    // DADOS DA SEGUNDA CARTA 02 //

    printf("ESTADO_02:");

    scanf("%s", estado2);

    printf("CIDADE: ");
    scanf("%s", cidade02);

    printf("CODIGO DE CARTAS: ");
    scanf("%s", codigocartas02);

    printf("PONTOS TURISTICOS: ");
    scanf("%d", &pontosturisticos02);

    printf("POPULACAO: ");
    scanf("%f", &populacao02);

    printf("PIB: ");
    scanf("%f", &pib02);

    printf("AREA EM KM²: ");
    scanf("%f", &area02);

    return 0;
}
