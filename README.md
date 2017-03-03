#include <iostream>
#include <conio.h>
#include <Windows.h>
using namespace std;
void main()
{
	long double i,j,k;
	for(i=0;i<24;i++)
	{
		for(j=0;j<60;j++)
		{
			for(k=0;k<60;k++)
			{
				cout<<endl;
				cout<<i<<" : "<<j<<" : "<<k<<endl;
				cout<<endl;
				Sleep(1000);
				system("cls");
			}
		}
	}
	getch();
}
