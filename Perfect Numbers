/*
In number theory, a perfect number is a positive integer that is equal to the sum of its positive divisors, excluding the number itself. For instance, 6 has divisors 1, 2 and 3 (excluding itself), and 1 + 2 + 3 = 6, so 6 is a perfect number.
*/
#include <stdio.h>

int main(void) {
  int num;
  printf("Enter a number:");
  for(num=1;num<1000000;num++){
   int sum=0;
   for(int i=1;i<=num/2;i++)
    if(num%i==0){
      sum+=i;
      if(sum>num)
           break;
    }
   if(sum==num)
    printf("%d is a perfect number\n",num);
  } 
    
  return 0;
}
