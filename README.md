#include <stdio.h>
int main()
{
   int x=1;
   if(x--)
      printf("hello");
      --x;
    else
       printf("%d",x);
    return 0;
}
//output: compiler error
