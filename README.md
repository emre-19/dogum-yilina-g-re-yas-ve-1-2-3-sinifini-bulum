# dogum-yilina-g-re-yas-ve-1-2-3-sinifini-bulum




#include<stdio.h>      /*şu anki yıl 2018*/    /*1.sinif 7 yasinda 
                                               2.sinif 8 yasinda
                                               3. sinif 9 yasinda*/
int main() {                                   
	int sinif,yas,yil;
printf("dogum yilinizi giriniz\n");
scanf("%d",&yil);

yas=2018-yil;

switch (yas) {


case 7:
{
	printf("7 yasindasiniz ve 1. sinifsiniz");
	break;
}
case 8:
{
	printf("yasiniz 8 ve 2. sinifsiniz");
	break;
}
case 9:
{
	printf("yasini 9 ve 3. sinifsinz");
	break;
}

default: printf("yaslis girim"); break;

}


return 0;

}
