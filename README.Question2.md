# Quiz-7q2
Quiz


/*
Quiz #7
Main: Triangles
By: Jorge Cervantes
#TC1017
Referencia: XXXXXXXXXX
---------------------------------------------------------------------
*/

#include <iostream>
using namespace std;


int triangle1(int x){
int xx = x, i;

	for(int ii = 0; ii < x; ii ++){
	int i = x;
		do{
			if(i < xx){
				i = i + 1;
				cout << "T";
			}

		}while(i < xx);

		xx = xx + 1;
		cout << endl;
	}
return 0;
}

int triangle2(int x){
int u = x;

	for(int ii = 0; ii < u; ii++){

		for(int i = 0; i < x; i++){

			cout << "T";
		}

	x = x - 1;
	cout << endl;
	}

return 0;
}

int main(){
int x;
	cout << "Which is the size of your triangle \n";
	cin >> x;
	cout << endl;

	triangle1(x);
	triangle2(x);

return 0;
}
