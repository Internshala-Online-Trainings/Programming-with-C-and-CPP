Below are the codes which are used in the video.

Program 1
#include <stdio.h>
int main( )
{
  auto int a = 1;
  {
    auto int a = 2;
    {
      auto int a = 3;
      printf ( "\n%d ", a);
    }
    printf ( "%d ", a);
  }
  printf( "%d\n", a);
}


Program 2
#include<stdio.h>
int fun()
{
  int count = 0;
  count++;
  return count;
}
  
int main()
{
  printf("%d ", fun());
  printf("%d ", fun());
  return 0;
}