/* Ejemplo 1 de la Matriz Proyecto Compiladores sin punteros
	Funcionamiento de una tabla leyendo
	Funcionamiento de una tabla escribiendo sus datos*/

#include<stdio.h>

int main() {
	
	int tabla [3][4];
	
	printf ("\n Ingrese valores para guardar en tabla de 3 x 4: \n");
	
	for(int i=0; i<3; i++) {
		for(int j=0; j<4; j++) {
			printf(" Elemento [%d , %d] : ", i, j);
			scanf("%d", &tabla[i][j]);
		}
		printf("\n");
	}
	
	printf("\n La tabla almacenada es:\n\n");
	
	for(int i=0; i<3; i++) {
		for(int j=0; j<4; j++) {
			printf("%3d", tabla[i][j]);
		}
		printf("\n");
	}
	

	
	return 0;
}
