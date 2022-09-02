# variables

#include <iostream>
using namespace std;
void main()
{
	float drobi = 1.5321342;
	double drob = 3.53423423423432; /* double может вместить больше чисел после
									запятой чем float */
	int a = 4; // самый обычный integer
	short b = 32767; // тип данных short принимает значения в диапозоне от -32768 до 32767
	long c = 23443321; // тип данных long ничем не отличается от int, но их можно комбинировать
	char word = 'A';
	bool Tr = true;
	bool Fl = false;
	cout << drobi << " " << drob << " " << a << " " << b << " " << c << " " << word << " " << Tr << " " << Fl; // Вывод в консоль
}
