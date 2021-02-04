/*求两个整数的和和用自定义函数编写*/
#include<stddio.h>
int main(){
  int a,b,c;
  int add(intx,inty);   //函数声明，声明本函数要调用的add 函数
  scanf("%d %d",&a,&b);
  c=add(a,b);          //调用add函数，将函数的返回值赋给c
  printf("c=%d",c);
  }
  int add(intx,inty)//定义函数值为整型，形式参数x、y为整型的add函数
  {int z;
  z=x+y;
  return (z);    //返回z的值到该函数被调用处
}
