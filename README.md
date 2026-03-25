# M2-D4-SEB
AIM:
Write a c program to find the sum of digits using dowhile loop.
PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,sum=0,digit;
    scanf("%d",&a);
    for(;a!=0;a=a/10)
    {
        digit=a%10;
        sum+=digit;
    }
    printf("%d",sum);
}
```
OUTPUT:
<img width="651" height="284" alt="image" src="https://github.com/user-attachments/assets/c2010257-314a-4258-9964-c5d1c436101d" />
RESULT:
Thus the code run successfully!
