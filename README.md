- 👋 Hi, I’m @xiugod
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
xiugod/xiugod is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
int get_s(int a, int b) 
{

	int z = a + b;
	return z;
}

int main()
{
	int c, d;
	scanf_s("%d %d", &c, &d);
	int x = get_s(c,d);
	printf("%d\n", x);
	return 0;
}
