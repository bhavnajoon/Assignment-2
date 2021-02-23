# Assignment-2
#include<stdio.h>
int main()
{
   int i,j,a[3][3];
   printf("enter the array");
   for(i=0;i<3;++i)
   {
      for(j=0;j<3;++j)
      {
         scanf("%d",&a[i][j]);
      }
   }
   printf("the elements in the matrix:\n");
   for(i=0;i<3;++i)
   {
      for(j=0;j<3;++j)
      {
         printf("elements-a[%d][%d]=%d\n",i,j,a[i][j]);
      }
   }
   printf("the matrix is :\n");
   for(i=0;i<3;++i)
   {
      for(j=0;j<3;++j)
      {
         printf("%d",a[i][j]);
      }
      printf("\n\n");
   }
   return 0;
}   
