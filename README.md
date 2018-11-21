# Carrito
author Cristian arauz
carrito
#include<stdio.h>
main()
{
	int vector[3];
	vector[0]=10;
	vector[1]=20;
	vector[2]=30;
	
	for(int i=0;i<=2;i++)
	
	{
		printf("\n Deme vector [%d] ",i);
		scanf("%d",&vector [i]);
    }
	for(int i=0;i<=2;i++)
		printf("\n v[%d]=%d",i, vector[i]);
	/*printf("%d", vector [0]);
	printf("%d", vector [1]);
	printf("%d", vector [2]);*/
	
}


promedio  de edades 


#include<stdio.h>
main()
{
	float edades[10];//declaramos  un grupo de  10 elementos 
    float promedio;
	//leemos las edades
	for(int i=0;i<=9;i++)
	{
		printf("\n Deme edad [%d] ",i);
		scanf("%f",&edades[i]);
    }
    //sumamos las edades
    
    promedio=0;
    for(int i=0;i<=9;i++)
       promedio=promedio+edades[i];
       
    //calculamos el promedio 
    
    promedio=promedio/10;
    
    //imprimos resultados
    
    printf("\nEdades ingresadas fueron ");
	for(int i=0;i<=9;i++)
		printf("\n edades[%d]=%f",i, edades[i]);
		
	printf("\n\n El promedio de edades es %f ",promedio);
	
}
