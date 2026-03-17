# atv-girotto1
1-
#include <stdio.h>
int main(){
	int A[10];
	printf("escolha os dois primeiros numeros: ");
	scanf("%d %d", &A[0], &A[1]);
	for(int i = 2; i < 10, i++);
	{
		if((i + 1) %2 !=0){
			A[10] = A[i - 1] + A[i - 2];
			}
			else{
				A[10] = A[i - 1] - A[i - 2];
		}
			printf("Sequencia: ");
			for(int = 0; i < 10, i++);{
				("%d", A[i]);
			}
	}
	return 0;
}
