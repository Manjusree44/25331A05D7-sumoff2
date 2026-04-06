#include<stdio.h>

int main(){
int a, b, c, max;
printf(“25331a05d7\n”);
printf("enter 3 nos");
scanf("%d %d %d", &a, &b, &c);

max = (a > b && a > c) ? a : (b > c ? b : c);
printf(" the max no is : %d\n ", max);

return 0;
}

