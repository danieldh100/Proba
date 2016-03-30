#include <stdio.h>
#include <stdlib.h>

float fator(float numero)
{
   if(numero > 1)
      return numero * fator(numero - 1);
   else
      return 1;
}

int main(){

	float p=0,x=0,n=0,cnp=0;
	
	printf("Entre com n: ");
	scanf("%f",&n);
	printf("Entre com x: ");
	scanf("%f",&x);
	printf("Entre com p: ");
	scanf("%f",&p);
	cnp = fator(n) / (fator(p) * fator(n-p));
	printf("%f\n\n",cnp);
	
}
