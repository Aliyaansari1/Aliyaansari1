#include<stdio.h>

int main()
{  
    int i,j,m,n,temp,min;
    int a[]={5,7,2,8,1};
    for(i=0;i<n-1;i++)
       {
          min=i;
          for(j=i+1;j<n;j++)
              {
                if(a[j]<a[min]);
                    min=j;
              }          
                  temp=a[i];
                  a[i]=a[min];
                  a[min]=temp;
              }    
                printf("printed sorted, array using selection sort=\r");
                for(i=0;i<n;i++)
              { 
                printf("%d",a[i]);
              }
              
    return 0;
    
}
include <stdio.h>

int main() 
{
    int i,j;
    for(i=1;i<=3;i++)
    {
        for(j=1;j<=i;j++)
        {
            printf("* ");
        }
        printf("\n");
    }
    for(i=3;i>=0;i--)
    {
        for(j=0;j<=i;j++)
        {
            printf("* ");
        }
        printf("\n");
    }
    
    
    return 0;
}
