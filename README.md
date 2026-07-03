#include<stdio.h>
int main(){
int id=261006812;
int digits[20];
int sum=0, i=0;

while (id>0){
    digits[i]=id%10;
    sum+=digits[i];
    id/=10;
    i++;
}
 printf ("sum of digits=%d\n",sum);
 return 0;
}
