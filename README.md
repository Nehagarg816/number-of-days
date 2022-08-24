# number-of-days
This is a program for finding number of days in a month of a year using switch case.


#include<stdio.h>
#include<conio.h>
void main()
{
	int month,year;
	printf("Enter year number:");
	scanf("%d",&year);
	printf("Enter month number:");
	scanf("%d",&month);
	switch(month)
	{
		case 1:
			printf("Number of days are 31");
			break;
		case 2:
			if(year%4==0)
			{
				printf("Number of days are 29");
			}
			else
			{
				printf("Number of days are 28");
			}
			break;
			
		case 3:
			printf("Number of days are 31");
			break;
			
		case 4:
			printf("Number of days are 30");
			break;
			
		case 5:
			printf("Number of days are 31");
			break;
			
		case 6:
			printf("Number of days are 30");
			break;
			
		case 7:
			printf("Number of days are 31");
			break;
			
		case 8:
			printf("Number of days are 31");
			break;
			
		case 9:
			printf("Number of days are 30");
			break;
			
		case 10:
			printf("Number of days are 31");
			break;
			
		case 11:
			printf("Number of days are 30");
			break;
			
		case 12:
			printf("Number of days are 31");
			break;
		default:
			printf("Invalid choice");
	}
}
