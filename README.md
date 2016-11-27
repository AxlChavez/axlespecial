//Area de un triangulo
#include<stdio.h>
float A;
float B;
float R;
#define Div 2
int main(){
	printf("Ingrese altura");
	scanf("%f",&A);
	printf("Ingrese base");
	scanf("%f",&B);
	R=B*A;
	R=R/Div;
	printf("El area es : %.2f\n\n",R);
	system("pause");
	return 0;
	
}
