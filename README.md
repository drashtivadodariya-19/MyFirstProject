# MyFirstProject
NAME : Drashti R Vadodariya
APPLICATION NO : JUUG25BTECH15530
BRANCH : AIDE-A
SUBJECT : Introduction to probproblem solving
DATE : 19/11/2025

#include <stdio.h>
int main() 
{
    int n, r= 0;

    printf("Enter a 3-digit number: ");
    scanf("%d", &n);

    if (n>=100 && n<=999)
	 {
        while (n!= 0) 
		{
            r= r*10+n%10;
            n/= 10;
        }
        printf("Reversed number: %d\n",r);
    } else 
	{
        printf("Please enter a valid 3-digit number.\n");
    }

    return 0;
}
