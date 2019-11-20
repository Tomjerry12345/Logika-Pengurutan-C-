#include <iostream>
#include <cstdlib>
#include <conio.h>

using namespace std;

int main()
{
	int data[20];
	int tmp , n;
	
	cout << "inputkan banyak data : ";
	cin >> n;
	for (int i = 0; i < n; i++)
	{
		cout << "data ke- " << i << " ";
		cin >> data[i];
	}
	
	cout << "Data yang di urutkan \t";
	for (int i = 0;i < n;i++)
	{
		cout << data[i] << " ";
	}
	for (int i = 0; i < n - 1;i++)
	{
		for (int j = 0; j < n; j++)
		{
			if (data[i] > data[j])
			{
				tmp = data[i];
				data[i] = data[j];
				data[j] = tmp;
			}
			cout << "\nData yang telah di urutkan \t:";
			for (int i = 0;i < n;i++)
				cout << data[i] << " ";
				cout << endl;
			getch();
		}
	}
}
