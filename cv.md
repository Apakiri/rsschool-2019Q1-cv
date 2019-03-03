###### Resume
# Apanasiuk Kirill
## contacts:
* phone number:**+375291753316**
* [mail](Micapka@yandex.ru)
* [VK](https://vk.com/id193756100)
## Summary
I want to be and will be a programmer. About myself I can say that I am sociable and inquisitive. I like to discover something new and study the unknown. I will make every effort to become the best expert in my field.
## Skills and Technologies 
* HTML5,  CSS;
* basic Jx;
* basic C++
* basic JavaScript;
* Git;
## Code examples
```
#include<iostream>
using namespace std;

void fill_mass(int arr[], int size)
{
	for (int i = 0; i < size; ++i)
	{ 
		cin >> arr[i];
	}

}
void display_mass(int arr[], int size)
{
	for (int i = 0; i < size; ++i)
	{
		cout<<endl<<arr[i];
	}
}
int sum_of_el(int arr[], int size)
{
	int sum = 0;
	for (int i = 0; i < size; ++i)
	{ 
		sum += arr[i];
	}

	return sum;
}


int main()
{
	int sizeA,sizeB;

	cout << "Enter size of massA "<<endl;
	cin >> sizeA;
	int*massA = new int[sizeA];
	cout<< "Enter size of massB "<<endl;
	cin >> sizeB;
	int*massB = new int[sizeB];

	cout << "Enter elements of massA" << endl;
	fill_mass(massA, sizeA);

	cout << "Enter elements of massB" << endl;
	fill_mass(massB, sizeB);

	if (sum_of_el(massA, sizeA) <= sum_of_el(massB, sizeB))
	{
		cout << "Elements of massA" << endl;
		display_mass(massA, sizeA);
		cout << endl<<"Elements of massB" << endl;
		display_mass(massB, sizeB);
		cout << endl;
	}
	else
	{
		cout << "Elements of massB" << endl;
		display_mass(massB, sizeB);
		cout << endl<<"Elements of massA" << endl;
		display_mass(massA, sizeA);
		cout << endl;
	}

	system("pause");
	return 0;
}
```
## Expirience 
* completed courses: CodeAcademy: 
                                 * HTML;
                                 * CSS;
*  practice in university on C++; 
## Education
##### Higher education  
**Belarusian State University of Informatics and Radioelectronics, Faculty of information technologies and control, Control Systems, Minsk.**       
Year of ending - 2021.  
###### Courses
* RollingScopes Js;
## Languages  
English B1;
