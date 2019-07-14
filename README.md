#include <stdio.h>

int main()
{
  int i,j,n;
  printf("enter the no of rows");
  scanf("%d",&n);
  for (i=1;i<=n;i++)
  {
      printf("\n");
      for (j=5;j>=i;j--)
      {
          printf("*");
      }
  }

    return 0;
}
