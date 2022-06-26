# dividing-a-num-upto-it-equals-to-0-and-adding-those-quoitents 
#include<stdio.h>
int main(){
int a,b,s=0,r;
    scanf("%d%d",&a,&b);
    while(r!=0){
        r=a/b;
        s=s+r;
        r=r/b;
    }
    printf("%d",s);
    }
    
