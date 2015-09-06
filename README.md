# bubble-sort
#define max 100
#include<stdio.h>
#include<conio.h>
void main()
{
  int a[max],i,j,size,temp=0;
  clrscr();
  printf("\nEnter the size of array");
  scanf("%d",&size);
  printf("\nEnter elements in the array");
  for(i=0;i<size;i++)
    scanf("%d",&a[i]);
     printf("\nThe sorted array is");
     for(i=size-1;i>=0;i--)
       {
          for(j=i-1;j>=0j--)
            { 
               if(a[i]<a[j])
               {
                 temp=a[i];
                 a[i]=a[j];
                 a[j]=temp;
                 }
            }
        }
        for(i=0;i<size;i++)
        printf("\n%d",a[i]);
        getch();
  }
