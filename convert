#include <iostream>
#include <locale.h>

using namespace std;
 
int menu;

int c2f(int c) 
{
	int resultC2F = (c * 9/5) + 32;
	
	return resultC2F;
}

int f2c(int f) 
{
	
	int resultF2C = (f - 32) * 5/9;
	
	return resultF2C;
}	

 
int main() {
	setlocale(LC_ALL, "Portuguese");
	while (menu != 1 && menu != 2) {
	cout << "Digite 1 se quer converter C° para F°\n" <<
			"Digite 2 se quer converter F° para C°\n";
			
	cin >> menu;
	switch (menu) {	
	case 1:
		int c;
		cout << "Digite o valor em C°";
		cin >> c;
		cout << c << "°C em F°, é: " << c2f(c) <<"F°\n";
	break;
		
	case 2:
		int f;
		cout << "Digite o valor em F° ";
		cin >> f;
		cout << f << "°F em C°, é: " << f2c(f) <<"C°\n";
	break;
	}	
	
	if (menu != 1 && menu != 2) {
		cout << "A opção " << menu <<" é inválida\n";
	}
	
}
 	return 0;
 
 }
 
