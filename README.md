# scope-of-variable
//scope of variable

#include<stdio.h>
void main()
{
	int a=10,b=20;
	printf("%d \t%d\n",a,b);
	{
		int a=50;
		b=60;
		printf("%d\t%d\n",a,b);
		
	}
	printf("%d \t%d\n",a,b);
}
