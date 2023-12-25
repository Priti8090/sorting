#include <stdio.h>

int main()
{
    int i,j, k;
    int a[10];
    printf("Enter a list of array:");
      for(i=1;i<10;i++)
    {
        scanf("%d",&a[i]);
    }
    for(i=1;i<9;i++)
    {
        k=a[i];
        for(j=(i-1);j>=0;j--)
        {
            if(a[j]>k)
            a[j+1]=a[j];
            else
            break;
        }
        a[j+1]=k;
    }
    printf("Your sorted array is:\n");
    for(i=0;i<9;i++)
    printf(" %d",a[i]);

    return 0;
}


