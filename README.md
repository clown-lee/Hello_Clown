# Hello_Clown
First repository of mine

Hi!Everyone!
This is my first file, or you can call it repository:p,and I come to this amazing place to find something interesting!
Love CODING!!!!!!!!!!!!!!!!:D
***********this is for testing************

******************************************subscribe*************************************************************
A truck broke the traffic rules and ran away after hitting someone. Three people at the scene witnessed the incident, but did not remember the car number, only some of the characteristics of the car number. A said: the first two digits of the car number are the same; B said: the last two digits of the car number are the same, but different from the first two; C is a mathematician, he said: the number of four is exactly an integer square. Please program according to the above clues to help the police find out the car number, so as to solve the case as soon as possible and catch the traffic offenders.
******************************************coding******************************************************************
#include<stdio.h>
#include<math.h>
int main()
{
	int a,b,m,n,k;
	for(a=0;a<10;a++)
		{for (b=0;b<10;b++)
		{	m=a*1100;
			n=b*11;
			k=m+n;
			for (int i=1;i<100;i++)
			{
			if (a!=b&&pow(i,2)==k)
			{printf("%d,%d",k,i);
			}
         } 
		 }
         } 
 } 
