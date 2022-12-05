#include<stdio.h>
int main() {
int i,n;
printf("enter number:");
scanf ("%d",&n);
for(i=1;i<=n;i++) {
if(i%2==0) {
printf("%d",i);
}
printf("\n");
}
return 0;
}
