# 5.-odev

//kullan�c�dan girdi olarak pozitif bir tam say� alan ve 1 den o tam say�ya kadar olan say�lar�n toplam�n� bulan kodu yaz�n�z

#include<stdio.h>
int topla(int);
int main()
{
	int x;
	printf("sayiyi giriniz:");
	scanf("%d"  , &x);
	
	printf("toplam: %d " , topla(x));
	
	return 0;
}

int topla(int x)
{
	int i;
	
	for(i=1;i<=x;i++)
	{
		x=x+i;
	}
	
	return x;
}
