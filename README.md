- š Hi, Iām @xiugod
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
xiugod/xiugod is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
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
