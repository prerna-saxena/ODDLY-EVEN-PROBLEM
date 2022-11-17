# ODDLY-EVEN-PROBLEM



// Online C compiler to run C program online
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main() {
    int a=0, b=0, i, n;
    char num[100];
     
    printf("ENTER A NO\n");
    scanf("%s", num);
    n=strlen(num);
    while(n>0)
    {
        if(i==0)
        {
        a+=num[i-1]+48;
        n--;
        i=1;
        }
        
        else
       {
        b+=num[i-1]+48;
        n--;
        i=0;
    }
}
printf("%d", abs(a-b));
return 0;
}
