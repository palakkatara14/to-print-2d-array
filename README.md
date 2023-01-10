# to-print-2d-arraynclude <stdio.h>
#include<math.h>
int arms(int);

int main()
{
    int r;
    printf("enter range");
    scanf("%d",&r);
    for(int i=1;i<=r;i++)
    {
        arms(i);
    }

    return 0;
}
int arms(int a)
{
    int k=a,sum=0,d;
    int l=log10(a)+1;
    while(a!=0)
    {
        d=a%10;
        a=a/10;
        sum=sum +pow(d,l);
    }
    if(sum==k)
    printf("%d\n",k);
    
}nclude <stdio.h>
#include<math.h>
int arms(int);

int main()
{
    int r;
    printf("enter range");
    scanf("%d",&r);
    for(int i=1;i<=r;i++)
    {
        arms(i);
    }

    return 0;
}
int arms(int a)
{
    int k=a,sum=0,d;
    int l=log10(a)+1;
    while(a!=0)
    {
        d=a%10;
        a=a/10;
        sum=sum +pow(d,l);
    }
    if(sum==k)
    printf("%d\n",k);
    
}vv
