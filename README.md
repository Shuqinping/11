# 11
11
判断奇数偶数
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


输出1-100之间的奇数
int main()
{
	int i = 1;
	while (i <= 100)
	{
		if (i % 2 == 1)
			printf("%d " , i);
		i++;
	}
	return 0;
}



输出1-100之间的偶数
int main()
{
	int i = 2;
	while (i<=100)
	{
		if ((i-1)%2==1)
			printf("%d ", i);
		i++;
	}
		return 0;

}
