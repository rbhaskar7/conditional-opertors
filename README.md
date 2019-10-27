# conditional-opertors
all about if,else,if else,switch and algorithms associated with them
//program of if-else
#include<stdio.h>
int main()
{
  int a,b;
  printf("Enter two numbers:");
  scanf("%d %d",&a,&b);
  if(a>b)
  {
    printf("a is bigger");
  }
  else
  printf("b is bigger");
  return 0;
}


//program of switch
#include<stdio.h>
int main()
{
  int n;
  printf("Enter your choice.");
  printf("1.hi");
  printf("2.hello");
  scanf("%d",&n);
  switch(n)
  {
    case 1:printf("hi");
           break;

    case 2:printf("hello");
           break;

    default:printf("Wrong choice!!!");
  }
  return 0;
}
