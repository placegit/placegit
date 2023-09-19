- 👋 Hi, I’m @placegit
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
placegit/placegit is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include<stdio.h>
#include<stdlib.h>
int main(void)
{
	int i, num, count, sum=0;
	system("clear");
	printf("FOR LOOPS for cricket run in match\n\n");
	printf("Enter count:");
	scanf("%d",&count);
	for(i=0;i<count;i++)
	{
		printf("\nEnter number %d: ",i+1);
		scanf("%d",&num);
		sum=sum+num;
		printf("sum=%d",sum);
		
	}
	printf("\n\n");
	return 0;
}
