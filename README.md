# peso
#include<iostream>
using namespace std;
int main(){
	
	int peso = 0;
	
	cout << "informe seu peso: ";
	  cin >> peso;
	
	if(peso = 50){
	  peso * 25;
		cout << "Manter peso";
	}else if(peso < 50){
		peso * 30;
	    cout << "Emagordar.";
	}else if(peso > 50){
		peso * 20;
		cout << "Emagrecer.";
	}
return 0;
}
