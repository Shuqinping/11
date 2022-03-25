# 11
11
#include<stdio.h>
int main()
{
	int a = 5;
	int b = a % 2;//%模--取余数的意思
	if ( b == 1)//if语句后面不应该加上；
		printf("奇数\n");
	else
		printf("偶数\n");
	return 0;
}
