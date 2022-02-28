# Hafta5


#include <stdio.h>
#include <time.h>
#include<iostream>
#include <stdlib.h>

main()
{
    srand(time(NULL));
    int rastgele;
    float tekadet = 0,toplamtek=0;
    int sayac = 0;

    for(int i = 0; i < 10; i++)
    {
        rastgele = 1+ rand() % 100;

        if(rastgele % 2 == 1){
            printf("rastgele sayilar = %d \n",rastgele);
            toplamtek +=rastgele;
            tekadet += rastgele;
            sayac++;
        }
         else{
            printf("rastgele sayilar = %d \n",rastgele);

        }
    }
    printf("tek sayilarin adedi= %f\n",tekadet =sayac);
    printf("tek sayilarin toplami = %f ",toplamtek);
}
                          
                          
                          
                          
                          
                          
                          
                          
  #include<iostream>
using namespace std;

int main()
{
int i;
for(i=1;i<101;i++)
{
if(i%3==0)
{
if(i%7!=0)
{
cout << i << endl;
}
}
}
return 0;
}                        
                          
                          
                 
                 
                 
                 
                 
                 
                 
                 
                 
                 
                 
 #include<iostream>
using namespace std;
int main ()
{
     int toplam=0;
     for(int i=0; i<10;i++)
     {
         int puan;
         cout<<i+1<<". sayi :";
         cin>>puan
         ;
         toplam+=puan;
     }
     cout<<"Sayilarin toplami:"<<toplam;
      return 0 ;
     }                
