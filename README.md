# pattern-with-rows-input-from-user.c
// Online C compiler to print pattern with given rows // example enter no. of rows=10  ZYXWVUTSRQ ZYXWVUTSR ZYXWVUTS ZYXWVUT ZYXWVU ZYXWV ZYXW ZYX ZY Z  
// Online C compiler to print pattern with given rows
// example enter no. of rows=10

ZYXWVUTSRQ
ZYXWVUTSR
ZYXWVUTS
ZYXWVUT
ZYXWVU
ZYXWV
ZYXW
ZYX
ZY
Z


#include <stdio.h>

int main() {
    int i,j,n;
    printf("enter rows=");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        for(j=0;j<=(n-1)-i;++j)
        printf("%c",90-j);
        printf("\n");
    }
    return 0;
}
