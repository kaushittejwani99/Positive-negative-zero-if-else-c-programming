# Positive-negative-zero-if-else-c-programming
This program is check a given no is Positive ,negative or zero using if-else-ladder.
#include<stdio.h>
#include<conio.h>

int main()
{
   int num;
   printf("This program make for know the given no is positive or not\n");

   printf("Enter any no.:-");
   scanf("%d",&num);
   if(num>0)
   {
     printf("%d is Positive no.\n",num);
   }
   else if(num<0)
   {
      printf(" %d  is Negative no.\n",num);
   }
   else
   {
	printf("The given no is not Positive or Negative.\n");
   }
   printf("\n          -----click Enter for exit --------      ");
   getch();
   return 0;
}
