# 2022c
資傳一甲ㄉ喔吼 :0

# week06
# 星星
#1

```cpp
#include <stdio.h>
int main()
{
    for(int i=1; i<=5; i++)
    {
        int star= i*2-1;
        printf("鷹架:%d樓 %d星\n", i, star);
    }
}
```
# 星星2
#2
```cpp
#include <stdio.h>
int main()
{
    for(int i=1; i<=5; i++)
    {
        int space = 5-i;
        int star = i*2-1;
        for(int k=0; k<space; k++)
        {
            printf(" ");
        }
        for(int k=0; k<star; k++)
        {
            printf("*");
        }

        printf("鷹架:%d樓 %d星\n", i, star);
    }
}
```

# 約分
#3
```cpp
#include <stdio.h>
int main()
{
    printf("請輸入兩個數字: ");
    int a, b, ans;
    scanf("%d %d", &a, &b);

    for(int i=1; i<a; i++)
    {
        if( a%i==0 && b%i==0) ans=i;

    }
    printf("找到ans:%d", ans);
}
```
# 輾轉相除法
#4
```cpp
#include <stdio.h>
int main()
{
    printf("請輸入兩個數字: ");
    int a, b, c;
    scanf("%d %d", &a, &b);

    while(1)
    {
        c = a%b;
        printf("a:%d b:%d c:%d\n", a, b, c);
        if( c==0 )
            break;
        a = b;
        b = c;
    }
    printf("中的是:%d",b);
}
```
# 一直做的迴圈
#5
```cpp
#include <stdio.h>
int main()
{
    int a=10;
    if(a>0) printf("a大於0\n");

    if( -999 ) printf("-999成立\n");
    if( -3 ) printf("-3成立\n");
    if( -2 ) printf("-2成立\n");
    if( -1 ) printf("-1成立\n");
    if( 0 ) printf("0不成立,所以升麼都沒印\n");
    if( 1 ) printf("1成立\n");
    if( 2 ) printf("2成立\n");
    if( 3 ) printf("3成立\n");
    if( 4 ) printf("4成立\n");
    if( 999 ) printf("999成立\n");
}
```
