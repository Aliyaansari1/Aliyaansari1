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
include<stdio.h>

int main() {
    int i,j,min, temp; 
    int a[]={5,7,2,8,1};
    for (i=0;i<4; i++)
    {
        min=i;
        for(j=i+1;j<5;j++)
        {
            if(a[j]<a[min])
        min = j;
    }
    temp=a[i];
    a[i]= a[min];
    a[min]=temp;
}
    printf("prented sorted array using selection sort=\n");
    for(i=0;i<5;i++)
    {
        printf("%d",a[i]);
    }
  return 0;
}