#include<stdio.h>
#include<string.h>
char a[10000],b[10000];
int main()
{
    int t,i,flag;
    scanf("%d",&t);
    while(t--)
    {
        scanf("%s",a);
        scanf("%s",b);
        if(strlen(a)!=strlen(b))
        {
            printf("No\n");
            continue;
        }
        for(i=0;i<strlen(a);i++)
        {
            if(a[i]==b[i]) flag=1;
            else if((a[i]=='a'||a[i]=='e'||a[i]=='i'||a[i]=='o'||a[i]=='u') && (b[i]=='a'||b[i]=='e'||b[i]=='i'||b[i]=='o'||b[i]=='u'))
                        flag=1;
                    else {
                            flag=0;
                            printf("No\n");
                            break;
                            }
        }
        if(flag) printf("Yes\n");
}
    return 0;
}
