#include <stdio.h>
#include <stdlib.h>

int main()
{
    while(1){
    system("color F5");
    int a, b, hasil, menu;
    float c, d, hasilbagi;
    printf("\n  PROJECT KALKULATOR SEDERHANA    \n\n");

            printf("  MENU :\n");
            printf("\t 1. Penjumlahan\n");
            printf("\t 2. Pengurangan\n");
            printf("\t 3. Perkalian\n");
            printf("\t 4. Pembagian\n\n");

    printf("  > Pilih Menu : ");
    scanf("%d" ,&menu);

    switch (menu){

        case 1 :
            printf("\n    ~ Penjumlahan ~ \n\n");
            printf("        Masukan bilangan pertama = ");
            scanf("%d", &a);

            printf("        Masukan bilangan kedua   = ");
            scanf("%d", &b);

            hasil    = a + b;
            printf("        Hasil penjumlahannya =  %d \n", hasil);
            printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
            break;

        case 2:
            printf("\n    ~ Pengurangan ~ \n\n");
            printf("        Masukan bilangan pertama = ");
            scanf("%d", &a);

            printf("        Masukan bilangan kedua   = ");
            scanf("%d", &b);

            hasil       = a - b;
            printf("        Hasil pengurangannya adalah =  %d \n", hasil);
            printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
            break;


         case 3:
            printf("\n    ~ Perkalian ~ \n\n");
            printf("        Masukan bilangan pertama = ");
            scanf("%d", &a);
            printf("        Masukan bilangan kedua   = ");
            scanf("%d", &b);

            hasil      = a * b;
            printf("        Hasil perkaliannya adalah = %d \n", hasil);
            printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
            break;

        case 4:
            printf("\n    ~ Pembagian ~ \n\n");
            printf("        Masukan bilangan pertama = ");
            scanf("%f", &c);
            printf("        Masukan bilangan kedua   = ");
            scanf("%f", &d);

            hasilbagi   = c / d;
            printf("        Hasil pembagiannya adalah = %.2f \n", hasilbagi);
            printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
            break;

            default:
            printf("Maaf, anda salah memilih menu.\n");
    }

}
    getch();

}
