#include <stdio.h>
int a[10];
void quick_sort(int low,int high)
{
    int j;
    if(low<high)
    {
        j=partition(low,high);
        quick_sort(low,(j-1));
         quick_sort((j+1),high);
    }
}
int partition(int low,int high)
{
    int i,j,pivot,temp;
    pivot=a[low];
    i=low;
    j=high;
    while(i<j)
    {
        while((a[i]<=pivot)&&(i<high))
        i++;
        
        while(a[j]>pivot)
        j--;
        if(i<j)
        {
            temp=a[i];
            a[i]=a[j];
            a[j]=temp;
        }
    }
    a[low]=a[j];
    a[j]=pivot;
    return j;
}
int main()
{
   int i; 
   printf("Enter a list of array to be sort :");
   for(i=0;i<10;i++)
   {
       scanf("%d",&a[i]);
   }
 quick_sort(0,9);
 printf("Your sorted array is :\n");
          for(i=0;i<10;i++)
         {
             printf("  %d",a[i]);
          }
   

    return 0;
}




