#include <stdio.h>
#define MAX 1000

int main(void) {

	int i=0,j=0;
    int a[MAX];
	printf("Press 0, once you are done with inputs\n");
	printf("Input : \n");
	while(1)
    {
        scanf("%d",&a[i]);
        if(a[i]==0)
           {
             break;
           }
            i++;
    }
    printf("Output :\n");

	for(j=0;a[j]!=42;j++)
	{
		printf("%d\n",a[j]);
		printf("\n");
	}


	return 0;
}
