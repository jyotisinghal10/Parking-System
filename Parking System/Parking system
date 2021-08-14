#include<stdio.h>
#include<conio.h>
#include<windows.h>
#include<stdlib.h>
void Bus();
void Cycle();
void Riksha();
int Menu();
void Show();
void Delete();
void gotoxy(int,int);
int nob,noc,nor,amount,count;
void main()
{
	long int i;
	int x=30,y=20;
 	gotoxy(x,y);
	printf("Parking Mangement System");
	Sleep(5000);
	Beep(2000,910);
	//for(i=0;i<=100000000;i++);
	while(1)
 {
 	system("cls");	
	switch(Menu())
	{
		case 1:
				Bus();
				break;
		case 2:	
				Cycle();
				break;
		case 3:
				Riksha();
				break;
		case 4:	Show();
				break;
		
		case 5:
				Delete();
				break;
		case 6:
				exit(0);
		default:
				printf("Invalid input");

	}
	getch();
  }	
}
void Bus()
{
	printf("Entry Sucess\n");
	nob++;
	amount=amount+100;
	count++;
	
}
void Cycle()
{
	printf("Entry Sucess\n");
	noc++;
	amount=amount+10;
	count++;
		
}
void Riksha()
{
	printf("Entry Sucess\n");
	nor++;
	amount=amount+50;
	count++;

}
int Menu()
{
	int ch;
	printf("1.Enter the Bus Entry\n");
	printf("2.Enter the Cycle Entry\n");
	printf("3.Enter the Riksha Entry\n");
	printf("4.Show status\n");
	printf("5.Delete data\n");
	printf("6.Exit\n");
	printf("Enter your choice\n");
	scanf("%d",&ch);
	return ch;
}
void Delete()
{
	nob=0;
	noc=0;
	nor=0;
	amount=0;
	count=0;
}
void Show()
{
	printf("Number of Bus %d\n",nob);
	printf("Number of Cycle %d\n",noc);
	printf("Number of Riksha %d\n",nor);
	printf("Number of Vehicle %d\n",count);
	printf("Total Amount %d\n",amount);
}
void gotoxy(int x,int y)
{
	COORD c;
	c.X=x;
	c.Y=y;
	SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE),c);
}
